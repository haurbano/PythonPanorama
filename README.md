# Panorama, joining two images
This is not my code, but works, the link to the blog (source) is [here:] (https://www.pyimagesearch.com/2016/01/11/opencv-panorama-stitching/)

## Thanks to the Author

[Author page] (https://www.pyimagesearch.com/author/adrian/)

## Notes:
The next instructions are thinking to run this python script in Ubuntu. But if you don't have a Ubuntu system, in the final part of this readme you can find a possible solution.

## To Run on Ubuntu:
### Requeriments:
1. Python 2.7.x
2. Install opencv-python with pip: `pip install opencv-python`
3. Install opencv-contrib-python: `pip install opencv-contrib-python`
4. Install numpy: `pip install numpy`
5. Install imutils: `pip install imutils`

### Steps
run: 
1. python stitch.py --first path/to/img1.png --second  path/to/img2.png

example:
1. python stitch.py --first images/bryce_left_01.png --second images/bryce_right_01.png

## To Run on Windows:
If you don't have a Ubuntu System you can install a Ubuntu machine on your Windows machine with the new Windows feature "Ubuntu on Windows", basically this is a Ubuntu 14 in your Windows but without any extra tool to install it.

The link to instructions: https://msdn.microsoft.com/en-us/commandline/wsl/install_guide

When you have your Ubuntu shell you can follow the Ubuntu instructions to run this repository, but with an extra requirement.

You need can show the generated images but your ubuntu system on windows don't have graphic interface, then you can install Xming to can show the images.

[Xming] (https://sourceforge.net/projects/xming/files/Xming/)

When Xming is already installed, run the next command in your shell of Ubuntu.

`export DISPLAY=:0`

This is a little explanation, I hope this helps.

## By Hamilton Urbano

