# FLAB-Putter
Open source putter that is (in theory) lie angle balanced. Heavily based on a LAB Mezz.

![ISO Front](https://github.com/ManBearPigWolf/FLAB-Putter/blob/main/Little%20FLAB%20Putter/ISO%20Front.png)
![ISO Rear](https://github.com/ManBearPigWolf/FLAB-Putter/blob/main/Little%20FLAB%20Putter/ISO%20Rear.png)
![Assembly](https://github.com/ManBearPigWolf/FLAB-Putter/blob/main/Little%20FLAB%20Putter/Assembly%20Process.gif)


A center shafted mallet style putter that should be very configurable. The idea is that the face insert and the shaft block should be able to be easily removed and swapped. I wanted the ability to change a milled face for a smooth face, or a change out the shaft on the course.

The files in the Little FLAB directory are what 90% of you should be using, the vast majority of people will not like the original FLAB because of the weight!

See the Little FLAB folder for a more regular weighted putter. ~~The putter is also very heavy in it's current state. This wasn't intentional at first, but with some real world testing it's actually been quite beneficial. The current theory is that because it has such a high MOI, paired with it being lie angle balanced, the putter is very difficult to twist in the stroke. Most people that have used it struggle with pace control for the first few rolls, but consistently hit their line. After adjusting to the weight, it's rolled well for almost everyone. However, it could probably still afford to lose some weight while maintaining a high MOI; finding the sweet spot will take some testing.~~ 

The main folder contains the original Solidworks files, both solidprt and assembly files. These would be useful for modifying the putter as all geometery and relations still exist in the file. The second folder contains STEP files which wouldn't be as easily modified, but can be directly uploaded to a fabrication website such a JLCCNC.com.

To make a putter you'd have your manufacturer of choice make: 1 x FLAB body, 1 x face insert, 1 x Shaft block (in the lie angle of your choice, or multiple if you want to change between shafts). You'll also need the various screws to hold the shaft block to the head and use as balancing weights under the putter. The file names for the screws are the part number you can order them as on McMaster-Carr, but they should also all be available locally at most hardware stores.

There's also a set of soft jaws to hold the face insert at a 3 degree angle to cut the face loft on a typical mill setup. I did it this way because I wanted texture on the face and JLCCNC didn't have an option for cutting a specific texture on the face. If however you don't have access to a mill, you can use the STEP file that has a 3 degree loft geometry already cut into the face and a smooth face would be just like plenty of Scotty Cameron or other putters on the market with a smooth face.

------------------------------UPDATE 6/19/2025------------------------------

Added a new version of the FLAB that reduces weight down to 509 grams total head weight (without the shaft). This was accomplished by making the putter smaller in the face to back direction, as well as a few mm smaller bottom to top side. The face is still just under an inch tall which should be comfortable for most players. 500 grams will still be heavier than most putters on the market, but it shouldn't feel like a sledge hammer which most people feel about the OG FLAB.

I configure the parts on JLCCNC as follows:
1. FLAB body - 6061 Aluminum, bead blasted + anodized, 0.1mm tolerance, no threads (I tap them myself)
2. Shaft block - 6061 Aluminum, bead blasted + anodized, 0.1mm tolerance
3. Face Insert - H59 Brass, bead blasted, normal tolerance

Using this configuration, the quote for the pieces is $135 dollars. However, tariffs are about as much as the pieces themselves bringing the total with shipping to just over $300. Tariffs really are the barrier on this project at the moment, if they weren't so high this would actually be a very affordable putter.

~~I haven't made the soft jaws for the new face insert yet, I'll do that closer to when the parts arrive.~~ That being said, this is still a beta version of the putter because I haven't recieved the parts to verify the fit of all parts; so use them at your own risk.

------------------------------UPDATE 6/22/2025------------------------------

Added the soft jaws that hold the face insert while machining the face loft to 3 degrees. The putter body's loft is 4 degrees right now (although it'd be simple to go higher if, say, you wanted arm lock loft), so that the face insert sits a little "proud" of the body. If you wanted a 4 degree face, the soft jaws could be modified to accomidate this and the face insert would sit flush into the body.

One thing to note that I learned on the OG putter, the face bent slightly during machining because it wasn't supported under the face during milling. The screws holding the face insert to the body still lined up and when I tighted the bolts it bent back into shape. However, if you know anything about machining, the fact that it bent during machining means it's not a true 3 degree loft anymore. I only bring it up because the V2 face insert is thinner than the original, and I'm sure the bending is going to be worse. I guess to mitigate this I'll take smaller cuts during the face milling. If you have the ability to put some form of a backing material behind the face during machining, you'd be doing yourself a favor. The proper way to go about it would be to hold the unlofted face square in a vice and set the mill head to a 3 degree cut, but tramming the head back square to the table after a cut is such a pain. If I were doing a larger quantity of face inserts instead of a single unit, I'd definitely do it the proper way; but for now the soft jaws are still my preferred option.

------------------------------UPDATE 7/10/2025------------------------------

I've received and assembled the Little FLAB and I'm totally in love with it! Some notes on the current state of the project:
1. The face insert was a little bit tight fitting into the body. I just had to take the sides in a few thousands of an inch with some sandpaper, so it wasn't a big deal. I've reduced the width in the model by .05mm so hopefully it fits perfect for you; but I have a feeling this was a tolerancing thing from the factory so it's probably a non-issue.
2. The heel weights have had the correct material applied for the center of gravity calculation and the shaft blocks have been updated to have the correct hosel alignment. I only have 3 lie angles currently, so the chances are that your lie angle isn't made yet. If you need a different lie angle or a lefty version, please create an issue on here or send me a direct message and I'll get one made and uploaded.
3. I've made a drawing for the body piece that shows tapping dimensions. This is useful when having JLCCNC quote the part, you can upload the dimension drawing to have them tap the holes at the factory. If you've never tapped a hole before, tapping blind holes like the weight ports can be tough, especially if you break a tap in the hole. Letting the factory figure it out will be better for most people.

I feel really good about the current state of the project, I love the slightly heavier weight of the head and it rolls balls so clean and pure. That said, if there's anything I can improve on or add to the design I'd love to make this as good of a putter as I can.


------------------------------UPDATE 7/23/2025------------------------------

I've updated the soft jaws to support the face during milling so that bending shouldn't be an issue, it'll also probably be easier to 3D print in the new design. I've also uploaded a lot more shaft blocks to the Little FLAB/STEP/ directory. There's now plenty of lie angles and even lefty versions, in both .370 and .355 hosel versions. Regardless, if you don't see the lie angle that fits you, make an issue on the repo and I'll get one generated.

As just a general update, I 3D printed a revealer that uses roller bearings instead of felt to support the shaft. It took some swapping of screw length in the weight ports to get the putter to balance, but I was eventually able to get it to balance pretty well! I had a friend bring over his genuine DF2.1 and DF3 putters, and both of them were about as balanced as my putter. I believe LAB uses felt on their revealer to give them a little wiggle room on balancing; so using roller bearings on my revealer will show if the putter is even slightly out of balance. The putter actually doesn't feel any different now that it passes a revealer test; which to me means to me that the truth about lie angle balancing, as it generally is, is in the middle. It seems that as long as a putter is reasonably within balance, it can help some people with putting, but the claims of how much torque affects a putting stroke are largely overstated. I'm also of the opinion that not every player benefits from a lie angle balanced putting stroke, as evidenced by the simple fact that nobody in at least the top 30 putters on tour (ranked by strokes gained putting) is currently using a zero torque putter.
