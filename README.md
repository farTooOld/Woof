# Woof
## A Screen - Image Measuring Tool

# What It Does:

• Displays current Screen Position of Target Reticle, Distance and Angle
• Scales a ‘Displayed Object’ (any Image on the Screen) using a 'Single' Known Horizontal Dimension
• Outputs a data file with saved Data Points. File is located in the folder of App’s location

## Platform Requirements:
Java8 (1.8) is required. For non-programmers, only the JRE is needed.
*** Use the Official Java, it's from Oracle ***

#### Place the .jar file in a Folder/Directory and Simply double-click the file to run it

## The GUI (Graphic User Interface):
• Optional ’Skins and Reticle’ [Right-Click Skin button]
• Left-Click the info button
• Remains ‘On Top’ of Windows for easy access
• Position (Distance) are the X/Y of Reticle with respect to Origin
• Length (L) is the Hypotenuse, Angle (ø) is with respect to Horizontal with 0º< range>+180º

## Usage:
• The Most Important aspect is: Any change in the Display of your Object (such as Window movement, Zooming…etc) Will affect/change your Scaling.
### TIP! Plan ahead: Move and Zoom your windows before scaling
• At boot-up, Pixel units are default and display is in Pixel units

• To set a new origin:
  – DragMe to new location for Origin
  – Click ‘New Origin

• To use Millimeter and Inch units (first Set a New Origin):
  – Then, DragMe to a Reference Location with a ‘Known’ dimension
  – Click ‘Scale It’
  – Select desired Units, Enter know value and Click ‘Set’
  – Note: Repeat as needed to ‘Re-Scale’ value or reset units type

## Collecting Data Points (if desired):
• DragMe to desired locations of interest
• Click ‘Data’ at each location
• Click ‘Save’ when finished
  – A data file (woofout.txt) is Written to the Same Location Where the App is Located!
  – Note: different platforms (Windows, Unix, Mac, Linux) manage ’Tabs’ inconsistently resulting in un-aligned data points

### TIP! 
After setting the Scaling, you can set new Origins and get Chain-dimensions from new Origin to the next DragMe point (DON'T reset the scaling - Simply observe the Distance/Length/Angle of the 'Point' of interest. Set another New Origin and repeat as desired

### Behind the Scenes (Info that’s good to know):
• Pixels are ‘Square’, not Round. DPI (Dots Per Inch) is not the correct Term used in Today’s World. PPI (Points Per Inch) is the current Term.

• Because Pixels are square, the calculated Scale value is applicable to both the Horizontal and Vertical directions.
• For simplicity, only the Horizontal (Dragged movement) is used for calculations

• Angles are measured with respect to the Origin and Horizontal line. Therefore, angles are calculated as soon as the Reticle moves from Origin.
Small distance movements, such as only a few pixels will result in the calculation but, being so close to Origin, angle’s are useless until at further distance.

### Errors and Bug’s:

• Hopefully no bugs. There are a few additional noteworthy considerations:
• Display of some items may show “?”, “∞”, or “infinity’ indicating an Input Value or a ‘User’ error. It should clear itself when mouse is moved or input is corrected

• The App is written in Java and, ‘Java’ can Behave, Look and Feel differently on various machines. A somewhat ‘Vanilla-Like’ layout is used to minimize differences. But, it’s not a perfect world.
