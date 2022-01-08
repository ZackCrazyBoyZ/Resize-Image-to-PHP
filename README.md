# Resize-Image-to-PHP
Script to resize PNG and JPG/JPEG image to any desired width and height

You can use this script to resize your PNG or JPG/JPEG image to any desired size read code before you use it to understand usage

Usage:
$resize = new ResizeImage('images/Be-Original.jpg');
$resize->resizeTo(100, 100, 'maxWidth');
$resize->saveImage('images/be-original-maxWidth.jpg');
