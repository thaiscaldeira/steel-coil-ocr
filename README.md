## Steel Coil OCR
Industrial OCR System for Hot Laminated Steel Coils

This is the repository for the codes related to the article "Industrial OCR System for Hot Laminated Steel Coils", submited to the Journal of Control, Automation and Electrical Systems.

The archives whose name starts with "ocrMultiFiles" contain the main processing algorithms. They receive the path for a folder with all archives to be processed, whose name contain the expected identification to be extracted from the images. The program also receives the path for the trained CNN, responsible for the classification tasks. After all the processing, two folders "Success Files" and "Fail Files" will be created in the initial folder indicated and the final processed images will be saved in them. In the Fail Files folder the original images will be saved as well for further analysis reasons. Three of these ocrMultiFiles are available, each one of them have different filtering alternatives, indicated in the file name. 
