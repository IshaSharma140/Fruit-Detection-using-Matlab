![Fruit Recognition System](https://github.com/IshaSharma140/Fruit-Detection-using-Matlab/blob/a187a9553b49340e0c53347c58154514c39682bf/Screenshot%202024-07-18%20201322.png)


# Fruit-Recognition
This project involves implementing a fruit recognition system using MATLAB. The system takes an input image and classifies it as either an Apple, Banana, Guava, or Strawberry by comparing it to a developed dataset using the Minimum Distance Criterion. The HSV color space is utilized, where the Hue and Saturation channels are used to extract average values of various statistical properties. Meanwhile, the Value channel is employed to create a texture map through the Gray Level Co-occurrence Matrix (GLCM), from which several textural properties are derived.

## Running the Project
Follow these steps:
1. Enter the full file path of the image you want to classify.
2. Read the provided instructions and type 'Y' to proceed.
3. Open the Colour Thresholder App and select the HSV Colour Space.
4. Use the polygon selection tool to draw around the Region of Interest (ROI). Adjust the selection using the appropriate sliders to refine it.
5. Click on Export, then confirm by clicking OK.
6. Close the Colour Thresholder App, return to the Command Window, and press any key to continue the program.
7. The binary mask and the foreground image will be displayed, and the name of the identified fruit will appear in the Command Window.
