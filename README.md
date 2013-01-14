# PanoStitch

This code implements OpenCV based panoramic image stitcher. Test input images along with 
the expected output are included here as well. There is a file called "CMakeLists.txt". 
This file will used to build the project (if you have built OpenCV using cmake). If not, 
just use the .cpp file in your project and build it. To build using command line, follow 
the steps below to get it up and running:

	$ make
	$ ./main IMG_0013.JPG IMG_0014.JPG IMG_0015.JPG IMG_0016.JPG

The output should be stored in "panoResult.jpg". You can change the output file name using the following flag:

	$ ./main IMG_0013.JPG IMG_0014.JPG IMG_0015.JPG IMG_0016.JPG --output myOutput.jpg