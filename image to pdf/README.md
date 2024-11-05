# Image to PDF Converter

This Python script converts images from a specified directory into a single PDF file. The resulting PDF is formatted to A4 size with specified font settings.

## Features

- Supports multiple image formats: PNG, JPEG, and JPG.
- Maintains the aspect ratio of images while scaling them to fit the A4 page.
- Configurable font settings for additional text (if needed).
- Automatically sorts images in alphabetical order before adding them to the PDF.

## Requirements

Make sure you have Python installed on your system. This script requires the following libraries:

- `Pillow` for image processing.
- `reportlab` for PDF generation.

You can install the required libraries using pip:

```bash
pip install Pillow reportlab



Usage
Clone or download this repository.
Place the images you want to convert in a directory.
Update the image_directory variable in the script to the path of your image directory.
Run the script:
python image_to_pdf.py

The output PDF will be generated in the current working directory and named output.pdf.

Customization
Image Directory: Change the image_directory variable in the script to point to your folder containing images.
Output PDF Name: Modify the output_pdf variable if you want to change the name of the output PDF.
Image Sizing: You can adjust the pdf_img.drawHeight to change the height of the images in the PDF.
Example
# Specify the directory containing images
image_directory = 'path/to/your/image/directory'  # Change to your image folder
# Output PDF file name
output_pdf = 'output.pdf'
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
This script uses the following libraries:

Pillow - Python Imaging Library
ReportLab - PDF generation library for Python

### Instructions to Create the `README.md`
1. Copy the text above.
2. Create a new file named `README.md` in the same directory as your Python script.
3. Paste the copied text into the `README.md` file.
4. Save the file.

Feel free to add more details or modify the sections to better suit your project! If you ne
