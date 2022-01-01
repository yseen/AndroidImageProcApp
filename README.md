# AndroidImageProcApp

An Android app for image processing. Based on the Color Blob OpenCV/Android tutorial. (OpenCV4Android Color Blob Detection - installation tutorial.htm)

When installing, take note of the OpenCVLibrary and jniLibs. (These binaries have been omitted from the git repository as they are much too large.)
Installation was performed on Android Studio version 4.1.3. (Note that, as of 29 August 2021, Android Studio 4.2 had bugs in the GUI which made it impossible to import the required libraries.)


Next step is to add in the computer vision functions from the PyVisionGUI project and improve the Android GUI to use these functions.
The classical image processing functions using OpenCV should work without trouble. 
The deeplap deep learning models for segmentation may take too long to run on a mobile processor. Tests must be performed.
