# Image Augmentation Script

This Python script performs various image augmentation techniques to artificially expand a dataset of images. It processes images from the `final_casia/` directory and saves augmented versions in the `augmented_2/` folder.

## Features
- **Rotation**:  
  - 90° clockwise  
  - 90° counter-clockwise  
- **Flipping**:  
  - Horizontal (left-right)  
  - Vertical (up-down)  
- **Brightness Adjustment**: Gamma correction for light/dark variations  
- **Resizing**: Adjusts image dimensions during transformations  

## Usage
1. Place original images in `final_casia/`  
2. Run the script to generate augmented versions:  
   ```python
   image_aug.py.

The script maintains the original image labels while appending transformation codes to filenames. Each transformation type uses a different numbering scheme to distinguish between augmentation types.
