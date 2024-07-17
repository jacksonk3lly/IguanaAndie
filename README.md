# Imperative Iguanas

## Team Members
- Alban Ribet
- Daniel Paxton
- Jackson Kelly
- Jack Murphy
- Kevin Wang

## Contributions

### Part 1 contributions:
- Sharpen filter - Jack
- Gaussian blur filter - Jack
- Median filter - Alban
- Image inversion - Kevin
- Colour channel cycling - Jackson
- Multilingual support - Alban
- Image resize - Kevin
- Image rotations: 90° left; 90° right; 180° - Daniel
- Image flip: Horizontal; Vertical - Daniel
- Image export - Jackson
- Exception handling & other error avoidance/prevention - Group

### Part 2 contributions:
- Toolbar - Kevin
- Colour picker - Kevin
- Mouse select - Daniel
- Crop - Daniel
- Draw - Daniel
- Macros - Jackson
- Extended Filters - Alban
- Keyboard shortcuts - Kevin
- Filters w/ negative - Jack
- Emboss Filters - Jack
- Sobel Filters - Jack
- Brightness - Jack
- Contrast - Jack
- Sidebar w/ sliders - Kevin
- Custom Colour chooser - Daniel
- Colour chooser sidebar - Kevin
- Icons - Daniel
- Multilingual support - Alban
- Troubleshooting & bug finding - Group
- Sidebar Preview - Daniel & Jackson
- Hue adjustment - Kevin
- Saturation adjustment - Kevin


###  Miscellaneous contributions:
- README - Kevin, Alban
- Keyboard shortcuts - Kevin
- UI theme - Daniel
- Undo/Redo, Save and Operation Jbutton Disabling - Jack
- Scroll wheel zoom - Kevin
- Draw image to scale - Daniel
- Image cycle: up, down, left, right - Daniel
- Image scramble - Daniel
- Preview windows - Jackson
- Save on Exit Window - Jack
- Status bar - Daniel
- ANDIE+ - Kevin
- Continuous Intergration - Alban
- JUnit Testing Gaussian Filter - Jack
- JUnit Testing Brightness and Contrast - Jack
- JUnit Testing SaveHelper - Jack
- Junit Testing ExtendedFilter - Jack
- JavaDoc - Alban, Kevin
- App Icon kindly provided by - Alex Dunn
- Custom Color Picker - Daniel
- Help Window layouts - Daniel
- Pencil Draw Tool - Daniel
- Star Draw Tool - Daniel
- Jar File - Jackson, Alban


<!--- Application Icon - see top of Andie.java -->

## Testing & Bugs

Testing throughout the earlier phases of development was generally completed through trial and error. Often manually with both expected and unexpected inputs. The person who implemented a feature was usually the one to test it. Later stages of development included the implementation of JUnit testing. This greatly reduced the number of accidental bugs in existing features.

**Known Bugs**
- 

## User Guide

### Introduction
Welcome to Andie, a non-destructive image editor. Andie provides various features for image manipulation, including editing, filtering, and viewing options.

### Menus

Andie offers the following menus located in the toolbar at the top of the window:

#### File
- **New Image**: Create a new image file.
- **Open**: Open an image file.

- **Save**: Save the current file.
- **Save As**: Save the current image with a new file name.

- **Export**: Export edited image in various formats.

- **Macro**: Macro Functions.

- **ANDIE+**: Link to better ANDIE.
- **Exit**: Close the application.

#### Edit
- **Undo**: Undo the last action.
- **Redo**: Redo the last undone action.

#### View
- **Zoom In**: Zoom in on the image.
- **Zoom Out**: Zoom out from the image.
- **Zoom Full**: Reset the zoom level to 100%.
- **Recentre View**: Reset the zoom level to 100%.

#### Image
- **Resize**: Resize the image to new dimensions.
- **Crop**: Crop image.

- **Rotate 90°**: Rotate the image 90 degrees clockwise.
- **Rotate -90°**: Rotate the image 90 degrees counterclockwise.
- **Rotate 180°**: Rotate the image 180 degrees.

- **Flip Horizontal**: Flip the image horizontally.
- **Flip Vertical**: Flip the image vertically.
- **Cycle Up**: Shift the image upwards in a cyclic manner.
- **Cycle Down**: Shift the image downwards in a cyclic manner.
- **Cycle Left**: Shift the image to the left in a cyclic manner.
- **Cycle Right**: Shift the image to the right in a cyclic manner.

- **Scramble**: Randomly rearrange the pixels in the image.
- **Random Scatter**: Randomly scatter the pixels in the image.
- **Block Average**: Pixelate the image.

#### Filter
- **Mean Filter**: Apply a mean filter to blur the image.
- **Soft Blur**: Apply a soft blur filter to the image.
- **Sharpen Filter**: Apply a sharpening filter to enhance image details.
- **Gaussian Filter**: Apply a Gaussian blur filter to the image.
- **Median Filter**: Apply a median filter to reduce noise in the image.
- **Emboss Filter**: Apply an emboss filter to the image.
- **Sobel Filter**: Apply a sobel filter to the image.

#### Colour
- **Greyscale**: Convert the image to greyscale.
- **Invert Colours**: Invert the image colour channels.
- **Cycle Colours**: Cycle the image colour channels.
- **Change Brightness**: Change the image brightness.
- **Change Contrast**: Change the image contrast.

#### Settings
- **Language**: Change the language of the application.

#### Help
- **Get Help and Infromation**: An about section for the application

### Keyboard Shortcuts

- **New Image**: `Ctrl + N`
- **Open Image**: `Ctrl + O`
- **Save Image**: `Ctrl + S`
- **Save As**: `Ctrl + Shift + S`
- **Export**: `Ctrl + Shift + E`
- **Open test Iguana**: `Ctrl + I`

- **Undo**: `Ctrl + Z`
- **Redo**: `Ctrl + Y`

- **Zoom In**: `Ctrl + +`
- **Zoom Out**: `Ctrl + -`
- **Zoom Full**: `Ctrl + 1`
- **Recentre Image**: `Ctrl + R`

- **Resize Image**: `Ctrl + 0`
- **Rotate Clockwise**: `Ctrl + R`
- **Rotate Counterclockwise**: `Ctrl + Shift + R`
- **Flip Horizontal**: `Ctrl + H`
- **Flip Vertical**: `Ctrl + V`

- **Mean Filter**: Apply a mean filter to blur the image. `Ctrl + M`
- **Soft Blur**: Apply a soft blur filter to the image. `Ctrl + B`
- **Sharpen Filter**: Apply a sharpening filter to enhance image details. `Ctrl + S`
- **Gaussian Filter**: Apply a Gaussian blur filter to the image. `Ctrl + G`
- **Median Filter**: Apply a median filter to reduce noise in the image. `Ctrl + Shift + M`

- **Greyscale**: Apply a soft blur filter to the image. `Ctrl + 5`
- **Invert Colours**: Apply a sharpening filter to enhance image details. `Ctrl + 6`
- **Cycle Colours**: Apply a Gaussian blur filter to the image. `Ctrl + 7`
- **Change Brightness**: `Ctrl + 8`
- **Change Contrast**: `Ctrl + 9`
- **Change Saturation**: `Ctrl + 0`
- **Change Hue**: `Ctrl + H`

### Language Settings

Andie supports multiple languages. To change the language, go to **Settings > Language** and select your preferred language then relaunch ANDIE.

### Saving Images

To save an edited image, go to **File > Save As**, choose the desired file format, and specify the file name and location.

### Exiting the Application

To exit Andie, simply go to **File > Exit** or close the application window.

## Try me!

- Sidebar minimise & maximise buttons
- Right Sidebar resize via click & drag
- File -> ANDIE+
- File -> New image

## Additional Comments

- Code often needs to be run using Gradle. VSCode sometimes turns up compiler errors for no apparent reason. 
<img width="1466" alt="Screenshot 2024-07-12 at 11 38 13 AM" src="https://github.com/user-attachments/assets/06683f65-747b-4b0e-8033-d400f47f4977">
