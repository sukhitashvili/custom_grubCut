**The script in the folder called *grabcut.py* helps to label images**

*Instructions*:

You can call the script from command line with additional argument **folder name** (where data is located):
> python grabcut.py data

After this two windows will show up, one for input and one for output. The output window will show 
what will be saved in *results* folder if you click *s* keyboard.

**At first**,  in input window,  draw a rectangle around the object using
mouse right button. Then press 'n' to segment the object (once or a few times)
For any finer touch-ups,  you can press any of the **keys below** and draw lines on
the areas you want. Then **again** press 'n' for updating the output.

>Key '0' - To select areas of sure background;

>Key '1' - To select areas of sure foreground;

>Key 'n' - To update the segmentation;

>Key 'r' - To reset the setup;

>Key 's' - To save the results in *results* folder and move to the next image;

>Key 'Esc'- To skip to the next image (nothing will be saved in *results* folder). 

**Also**, if input image size is too large you can resize input images to any desired size with such call:
> python grabcut.py data -H=200 -W=500

**and** images will opened and saved in such format.

