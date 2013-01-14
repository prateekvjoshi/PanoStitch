# PanoStitch

This code implements OpenCV based panoramic image stitcher. Test images along with the expected output are included in here as well. If you have built OpenCV using cmake, 
then follow the steps below to get it up and running:

	$ make

	$ ./main IMG_0013.JPG IMG_0014.JPG IMG_0015.JPG IMG_0016.JPG

The output should be stored in "panoResult.jpg". You can change the output file name using the following flag:

	$ ./main IMG_0013.JPG IMG_0014.JPG IMG_0015.JPG IMG_0016.JPG --output myOutput.jpg