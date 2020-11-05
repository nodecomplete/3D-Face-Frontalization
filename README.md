# 3D Face Frontalization

## Introduction

This application is a C++ Windows DirectX based tool used for viewing some of the output files from [Microsoft's Deep-3D-Face-Reconstruction project](https://github.com/microsoft/Deep3DFaceReconstruction). Deep3DFaceReconstruction takes a 2D image of a face and outputs a 3D mesh, cropped image and landmark files (eyes, nose and mouth). The tool displays the cropped image in the top-left quadrant. The 3D mesh, with the cropped image projected on to it, is displayed in the top-right quadrant. A shadow mapping technique is used to highlight in red the part of the mesh that is occluded in the original image (bottom-left quadrant). The 2D landmark coordinates for the left and right eye are projected from texture space to world space and displayed in blue. These landmarks are used to rotate the image (Yaw and Roll) and align it with the camera as can be seen in the bottom right quadrant.


## Building the software

1) The software was built using [Visual Studio 2019 community edition](https://visualstudio.microsoft.com/downloads/). Be sure to install the MFC module.

2) The DirectX [June 2010 DirectX SDK ](https://www.microsoft.com/en-nz/download/details.aspx?id=6812) must be installed.

## Using the software

To use the software, open a .mesh file from the sample data folder, or the drag the file from Windows Explorer on to the main application window

![alt text](https://github.com/nodecomplete/FaceView/blob/master/FaceView/ScreenShot.jpg)





 
