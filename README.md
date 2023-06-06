# Face_Detection



Hello dear friend,

If you want to use the Facebaserepo file, you need to create the images individually and organize these images according to the relevant code blocks.

How to do it?

Create the "data" and "aug_data" directories.
Inside the "data" directory, create directories named "images," "labels," "val," "test," and "train."
Inside the "train," "test," and "val" directories, create directories named "images" and "labels."
The "aug_data" section will be filled automatically.
After generating the images, you should use the "Labelme" application to mark the objects or people you want to recognize within a rectangular box. When the Labelme application is opened, direct the "dir" to the "images" folder and save the outputs in the "labels" folder. Make sure to enable auto-save as well. When framing the images in your project, always use rectangles.

Once you have created the relevant images and labels in your project, we need to convert this data to jpg format, and the code blocks will automatically handle this for you.

When you reach the "Partition Unaugmented Data" section, transfer only the images you have to the "train" (I transferred 70% to this section), "test," and "val" folders. Run the code and sit back.

In the line "img = cv2.imread(os.path.join('data','train', 'images','4df8b10c-ff09-11ed-923e-04cf4b415632.jpg'))," paste the name of your own image, and for the section below it, paste the name found in your own folders.
