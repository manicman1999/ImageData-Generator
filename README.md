# ImageData-Generator
Converts folders of images to chunks which can easily be saved/loaded into RAM (numpy).

Easily import your files and convert them to NumPy arrays.
Automatically saves the arrays in segments which can easily be loaded into RAM.

To use:

```python
dataGenerator(folder, im_size, mss = (1024 ** 3), flip = True, verbose = True)
```

folder: The directory, must be inside another folder named data.
im_size: The size each image should be resized to (ex. 128 = 128x128).
mss: Maximum Segment Size (in bytes), default 1GB.
flip: Toggle whether or not imported images should be duplicated and flipped.
verbose: Toggle whether the data generator prints information or not.




Feel free to steal this code for your own projects, and feel free to optimize it however you see fit!
