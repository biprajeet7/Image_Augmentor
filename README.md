# Image_Augmentor

This Python script performs various image augmentation techniques on a dataset of images to artificially expand the training data. The script applies transformations to images located in the final_casia/ directory and saves the augmented versions in the augmented_2/ folder.

Features
Rotation: 90 degrees clockwise and counter-clockwise

Flipping: Both horizontal (left-right) and vertical (up-down)

Brightness Adjustment: Gamma correction for light/dark variations

Resizing: Adjusts image dimensions during transformations

Usage
Place your original images in the final_casia/ directory

Run the script to generate augmented versions

Augmented images are saved in augmented_2/ with modified filenames indicating the transformations

The script maintains the original image labels while appending transformation codes to filenames. Each transformation type uses a different numbering scheme to distinguish between augmentation types.
