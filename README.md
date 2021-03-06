# image-toolkit
Tools to process images, implemented by opencv

## Content
### [License photo](./cli/license_photo.py)
To extract the person area from the given image and output the license photo with specified size and three background color
- to show the help information
    ```shell
    python cli/license_photo.py --help 
    ```
- process the given image and output the license format photo to $output_dir with three backgroud colors, blue, red, white, and in the default size of 1 inch
    ```shell
    python cli/license_photo.py --image_file $file_path --out_dir $output_dir
    ```
    
### [Resize iamge](./cli/resize.py)
To resize the image to specific size, if only width or height is given, the resize will keep the original ratio of width to height, if both width and height are given, the resize will resize to the desired size.

```shell
python cli/resize.py --image_file $file_path --out_dir $output_dir --width 800
```

### [Sketching](./cli/sketch.py)
To convert an image to sketch, you might want to use the sketch as your avatar.

```shell
python cli/sketch.py --image_file $file_path --out_dir $output_dir
```

