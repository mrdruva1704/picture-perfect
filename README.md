# Picture-Perfect
An MLH hackathon project. Image Selection
Sure, here's a sample README file for the provided Flask application code:

---

# Image Processing Web Application with Flask

This is a web application built with Flask, a lightweight Python web framework, for processing and categorizing images based on their structural similarity index (SSIM).

## Features

- **Upload Images**: Users can upload images to the application.
- **Blur Images**: Upon upload, the application applies a Gaussian blur to the images to simulate a mobile camera blur effect.
- **Categorize Images**: The application categorizes images as "good" or "bad" based on their SSIM score compared to reference images.
- **Download Images**: Users can download the "good" images as a zip file.

## Requirements

- Python 3.x
- Flask
- Pillow (PIL)
- torchvision
- piq

Install dependencies using:

```
pip install -r requirements.txt
```

## Usage

1. Clone this repository:

```
git clone https://github.com/your_username/image-processing-web-app.git
cd image-processing-web-app
```

2. Run the Flask application:

```
python app.py
```

3. Access the application in your web browser at [http://localhost:5000](http://localhost:5000).

## How It Works

- **Upload**: Users upload images through the web interface.
- **Blur**: Upon upload, the application adds a Gaussian blur to the images, simulating a mobile camera blur effect.
- **Categorization**: Images are categorized as "good" or "bad" based on their structural similarity index (SSIM) compared to reference images. The threshold for SSIM score is set at 0.11.
- **Download**: Users can download the "good" images as a zip file for further use.

## Contributing

Contributions are welcome! If you have suggestions, improvements, or feature requests, feel free to open an issue or submit a pull request.
