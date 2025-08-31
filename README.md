echo '# PNG to WebP Converter

A Python script that recursively converts PNG, JPG, and JPEG images to WebP format in a specified directory and its subdirectories.

## Features

- Recursively processes all subdirectories
- Converts PNG, JPG, and JPEG files to WebP format
- Automatically deletes original files after conversion
- Uses PIL (Pillow) library for image processing

## Usage

1. Set the `input_directory` variable to your target directory
2. Run the script: `python pngtowebp.py`

## Requirements

- Python 3.x
- PIL (Pillow) library: `pip install pillow`

## Example

```python
input_directory = "./charakter_bilder"  # Your image directory
```

## Warning

⚠️ **This script permanently deletes the original PNG/JPG files after conversion.** Make sure to backup your images before running!

## Supported Formats

- PNG → WebP
- JPG → WebP
- JPEG → WebP

The script maintains the same filename but changes the extension to `.webp`.' 
