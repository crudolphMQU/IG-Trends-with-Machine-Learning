# pythonIG
Python algorithm used with IG data

**TO DO:**
* Learn IG's API, set up IG business account and Facebook business account that are to be linked. 
* Add content to the IG accounnt (image with comments, likes) so that when the API is set up, a test webscrape can be done. Once successful, can move on to a real page (one of the tattoo artists')
* Image classification model building
* image preparation II: flattening and normalising images for the neural network. 
* Take into consideration the images have different dimensions. 
* Consider saving the prepped images into GCS to reduce run times. I believe if the we save the prepped image, we will simply load it into a new notebook instead of running the image-preparation notebook from the beginning. 

**DONE:**
* Organising images into subfolders for each object type in the image. 
* Instructions for mounting a bucket to be accessed as a folder in the JupterLab directory. 
* Created new instance to increase memory capacity so the images ccan be run without the kernel crashing. 
* Image preparation I: adding object type to the image filename. 

