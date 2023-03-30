# Dicom to PNG converter

This is a tool for converting DICOM images to PNG format. DICOM (Digital Imaging and Communications in Medicine) is a standard for storing medical imaging data, and is commonly used in radiology, cardiology, and other medical fields.

## Requirements

- Python 3.6 or higher
- PyDICOM
- numpy
- OpenCV
- matplotlib
- pandas
- tqdm
- PIL

## Usage

1. Clone this repository or download the script file.

2. Update the source directory and destination directory in the script to your own values:
    ```python
    src_dir = r'src_path'
    dst_dir = r'dst_path'
    ```

3. Run the script:
    ```sh
    python dcm_to_png.py
    ```

    The script will convert all the DICOM files in the source directory to PNG format and save them in the destination directory. The output files will have the same name as the input files, with the extension changed to .png.

## Credits

This tool was developed by Fabiha Bushra. Please feel free to use and modify this tool as you wish. If you have any questions or suggestions, please [open an issue](https://github.com/your/repo/issues).
