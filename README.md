# FLAB-Putter
Open source putter that is (in theory) lie angle balanced. Heavily based on a LAB Mezz.

A center shafted mallet style putter that should be very configurable. The idea is that the face insert and the shaft block should be able to be easily removed and swapped. I wanted the ability to change a milled face for a smooth face, or a change out the shaft on the course.

The putter is also very heavy in it's current state. This wasn't intentional at first, but with some real world testing it's actually been quite beneficial. The current theory is that because it has such a high MOI, paired with it being lie angle balanced, the putter is very difficult to twist in the stroke. Most people that have used it struggle with pace control for the first few rolls, but consistently hit their line. After adjusting to the weight, it's rolled well for almost everyone. However, it could probably still afford to lose some weight while maintaining a high MOI; finding the sweet spot will take some testing

The main folder contains the original Solidworks files, both solidprt and assembly files. These would be useful for modifying the putter as all geometery and relations still exist in the file. The second folder contains STEP files which wouldn't be as easily modified, but can be directly uploaded to a fabrication website such a JLCCNC.com.

To make a putter you'd have your manufacturer of choice make: 1 x FLAB body, 1 x face insert, 1 x Shaft block (in the lie angle of your choice, or multiple if you want to change between shafts). You'll also need the various screws to hold the shaft block to the head and use as balancing weights under the putter. The file names for the screws are the part number you can order them as on McMaster-Carr, but they should also all be available locally at most hardware stores.

There's also a set of soft jaws to hold the face insert at a 3 degree angle to cut the face loft on a typical mill setup. I did it this way because I wanted texture on the face and JLCCNC didn't have an option for cutting a specific texture on the face. If however you don't have access to a mill, you can use the STEP file that has a 3 degree loft geometry already cut into the face and a smooth face would be just like plenty of Scotty Cameron or other putters on the market with a smooth face.
