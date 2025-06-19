# FLAB-Putter
Open source putter that is (in theory) lie angle balanced. Heavily based on a LAB Mezz.

A center shafted mallet style putter that should be very configurable. The idea is that the face insert and the shaft block should be able to be easily removed and swapped. I wanted the ability to change a milled face for a smooth face, or a change out the shaft on the course.

The putter is also very heavy in it's current state. This wasn't intentional at first, but with some real world testing it's actually been quite beneficial. The current theory is that because it has such a high MOI, paired with it being lie angle balanced, the putter is very difficult to twist in the stroke. Most people that have used it struggle with pace control for the first few rolls, but consistently hit their line. After adjusting to the weight, it's rolled well for almost everyone. However, it could probably still afford to lose some weight while maintaining a high MOI; finding the sweet spot will take some testing

The main folder contains the original Solidworks files, both solidprt and assembly files. These would be useful for modifying the putter as all geometery and relations still exist in the file. The second folder contains STEP files which wouldn't be as easily modified, but can be directly uploaded to a fabrication website such a JLCCNC.com.

To make a putter you'd have your manufacturer of choice make: 1 x FLAB body, 1 x face insert, 1 x Shaft block (in the lie angle of your choice, or multiple if you want to change between shafts). You'll also need the various screws to hold the shaft block to the head and use as balancing weights under the putter. The file names for the screws are the part number you can order them as on McMaster-Carr, but they should also all be available locally at most hardware stores.

There's also a set of soft jaws to hold the face insert at a 3 degree angle to cut the face loft on a typical mill setup. I did it this way because I wanted texture on the face and JLCCNC didn't have an option for cutting a specific texture on the face. If however you don't have access to a mill, you can use the STEP file that has a 3 degree loft geometry already cut into the face and a smooth face would be just like plenty of Scotty Cameron or other putters on the market with a smooth face.

------------------------------UPDATE 6/19/2025------------------------------

Added a new version of the FLAB that reduces weight down to 509 grams total head weight (without the shaft). This was accomplished by making the putter smaller in the face to back direction, as well as a few mm smaller bottom to top side. The face is still just under an inch tall which should be comfortable for most players. 500 grams will still be heavier than most putters on the market, but it shouldn't feel like a sledge hammer which most people feel about the OG FLAB.

As I have thenm configured on JLCCNC as follows:
1. FLAB body - 6061 Aluminum, bead blasted + anodized, 0.1mm tolerance, no threads (I tap them myself)
2. Shaft block - 6061 Aluminum, bead blasted + anodized, 0.1mm tolerance
3. Face Insert - H59 Brass, bead blasted, normal tolerance

Using this configuration, the quote for the pieces is $135 dollars. However, tariffs are about as much as the pieces themselves bringing the total with shipping to just over $300. Tariffs really are the barrier on this project at the moment, if they weren't so high this would actually be a very affordable putter.

I haven't made the soft jaws for the new face insert yet, I'll do that closer to when the parts arrive. That being said, this is still a beta version of the putter because I haven't recieved the parts to verify the fit of all parts; so use them at your own risk.
