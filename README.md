# Simple ASCII Art Generator without any Library

This is a simple ASCII art generator that converts an image into ASCII art, using the Python Imaging Library (PIL). The ASCII art can be displayed in the terminal or written to a file.

## Requirements

- Python 3
- PIL (Python Imaging Library)

## Installation

To install PIL, run the following command in your terminal:
```bash
pip install pillow
``` 
## Usage

The ASCII art generator can be run from the terminal using the following command:

```bash
python ascii_art_generator.py image_path [-o output_file]
```

where `image_path` is the path to the input image file, and `output_file` is an optional argument that specifies the path to the output ASCII art file. If `output_file` is not specified, the ASCII art will be displayed in the terminal.

## Example

The following command will generate ASCII art from the image `example_image.jpg` and write it to the file `example_output.txt`:
```bash
python ascii_art_generator.py example_image.jpg -o example_output.txt
```
