When I run an image through `cv2.cvtColor(..., cv2.COLOR_RGB2GRAY)` manually, I get a single greyscale image as expected. When I call the same function from inside `MoviePy.editor.VideoClipFile.fl_image()`, I get a 3x3 grid like the Brady Bunch intro.

As far as I can tell, the data is identical, but MoviePy seems to interpret it differently.
