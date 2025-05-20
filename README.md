# nvx-ai-based-photoshop

AI-Based-Photoshop Simple is a web-based image editing application that leverages advanced AI techniques for seamless photo manipulation. Built with Flask, Mask R-CNN, OpenCV, and TensorFlow, it offers features such as image smoothing, filtering, and automatic background removal.

## Features

- **Automatic Background Removal**: Effortlessly remove backgrounds from images using Mask R-CNN.
- **Image Smoothing & Filtering**: Apply various smoothing and filtering effects to enhance your photos.
- **Web-Based Interface**: Edit images directly from your browser.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/nvx-ai-based-photoshop.git
   cd nvx-ai-based-photoshop
   ```

2. **Install Dependencies**

   - Ensure you have Python 3.x installed.
   - Install required libraries:
     ```bash
     pip install -r requirements.txt
     ```
   - Make sure you have TensorFlow 1.x and Keras > 2.0.6 installed.

3. **Download Mask R-CNN Weights**
   - Download the `mask_rcnn_coco.h5` file from the [Mask R-CNN GitHub repository](https://github.com/matterport/Mask_RCNN/releases).
   - Place the file in the appropriate directory as specified in the code.

## Usage

1. Start the Flask server:
   ```bash
   python app.py
   ```
2. Open your browser and navigate to `http://localhost:5000`.
3. Upload an image and select the desired operation (background removal, smoothing, filtering).

## References

- [Flask Documentation](https://flask.palletsprojects.com/)
- [Mask R-CNN by Matterport](https://github.com/matterport/Mask_RCNN)
- [OpenCV Documentation](https://opencv.org/)
- [TensorFlow Documentation](https://www.tensorflow.org/)

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/license/mit) file for details.

## Contact

For inquiries or feedback, please contact:

- Satria Nur Saputro: [satrianursaputro06@gmail.com](mailto:satrianursaputro06@gmail.com)
