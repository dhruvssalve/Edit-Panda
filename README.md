# Edit Panda - Image Format Converter

Edit Panda is a Python-based project aimed at simplifying the process of converting images to various formats, including JPEG, PNG, WebP, and more. Whether you need to convert a single image or batch process multiple images, Edit Panda has you covered. Additionally, it features a user-friendly web application developed using Flask and styled with Bootstrap for easy and intuitive image format conversion.

## Features

- Convert images to various formats, including JPEG, PNG, WebP, and more.
- Batch processing of images for efficient conversion.
- User-friendly web application for easy access and usage.
- Built-in CSS styling with Bootstrap for an attractive and responsive design.
- Utilizes the powerful OpenCV library for image processing.

## Requirements

To run Edit Panda, ensure you have the following dependencies installed:

- Python 3.x
- OpenCV
- Flask
- Bootstrap (included in the project)

## Installation

1. Clone the Edit Panda repository to your local machine:

   ```bash
   git clone https://github.com/dhruvssalve/edit-panda.git
   ```

2. Navigate to the project directory:

   ```bash
   cd edit-panda
   ```

3. Install the required Python packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Running the Web Application

1. Start the Edit Panda web application:

   ```bash
   python app.py
   ```

2. Open your web browser and navigate to [http://localhost:5000](http://localhost:5000) to access the Edit Panda user interface.

### Command-Line Usage

If you prefer to use Edit Panda via the command line, you can do so by running the following command:

```bash
python convert.py [OPTIONS] INPUT_FILE(S) OUTPUT_DIRECTORY
```

Replace `[OPTIONS]` with the desired format and any additional options, `INPUT_FILE(S)` with the path to your input image(s), and `OUTPUT_DIRECTORY` with the directory where you want to save the converted image(s).

## Supported Formats

Edit Panda supports the following image formats for conversion:

- JPEG
- PNG
- WebP
- Grayscale

## Contributing

Contributions to Edit Panda are welcome! If you want to contribute, please follow these steps:

1. Fork the Edit Panda repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to reach out to us if you have any questions or need assistance with Edit Panda. We hope you find this tool useful for your image format conversion needs!
