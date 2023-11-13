# Multiclass-Semantic-Segmentation-Annotation with tool-usage-codes

# Step by step guideline
* First, download the Fiji [software](https://imagej.net/software/fiji/?fbclid=IwAR26ajriJbLHJcDIoJU3g8RfrWojjTbk_Y72_qy8oqHdZ2wk9__TdMWOqDA) for annotating for semantic segmentation.
* Secondly, unzip and open the tool from ImageJ-win64.exe.
* Then follow: File (tab) > Open > desired_image > Plugins (tab) > Labkit > Open Current Image with Labkit
* Later, use **Draw, Flood fill, Erase** to draw masks for desired classes. To add more classes, click 'Add Label' button. Complete drawing mask accordingly for each classes. Don't forget to add background (can use Flood fill) at the end as a class.
* For each class, click the 'Export as Bitmap..' button to save the binary semantic segmentation mask image (in .tif format) for each class.
* Save all the binary mask for each class like previous step.
* Lastly, run the python code to make a multiclass semantic segmentation mask in grayscale.
