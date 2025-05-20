# NVX AI-Based Photoshop

**NVX AI-Based Photoshop** is a modern, web-based image editing application that harnesses advanced AI technologies for seamless and intuitive photo manipulation. Built with Flask, Mask R-CNN, OpenCV, and TensorFlow, this project provides powerful features such as automatic background removal, image smoothing, and filtering—all accessible through a user-friendly browser interface.

## Features

- **Automatic Background Removal**  
    Instantly remove image backgrounds using state-of-the-art Mask R-CNN models.
- **Image Smoothing & Filtering**  
    Enhance your photos with a variety of AI-powered smoothing and filtering effects.
- **Web-Based Interface**  
    Edit images directly in your browser—no installation required beyond the server.

## Installation

1. **Clone the Repository**
     ```bash
     git clone https://github.com/yourusername/nvx-ai-based-photoshop.git
     cd nvx-ai-based-photoshop
     ```

2. **Install Dependencies**
     - Ensure Python 3.x is installed.
     - Install required packages:
         ```bash
         pip install -r requirements.txt
         ```
     - Confirm TensorFlow 1.x and Keras > 2.0.6 are installed.

3. **Download Pretrained Weights**
     - Obtain `mask_rcnn_coco.h5` from the [Mask R-CNN releases page](https://github.com/matterport/Mask_RCNN/releases).
     - Place the file in the directory specified in the project code.

## Usage

1. Launch the Flask server:
     ```bash
     python app.py
     ```
2. Open your browser and navigate to [http://localhost:5000](http://localhost:5000).
3. Upload an image and select your desired operation (background removal, smoothing, or filtering).

## Documentation & References

- [Flask Documentation](https://flask.palletsprojects.com/)
- [Mask R-CNN by Matterport](https://github.com/matterport/Mask_RCNN)
- [OpenCV Documentation](https://opencv.org/)
- [TensorFlow Documentation](https://www.tensorflow.org/)

## Contributing

We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Create a feature branch:
     ```bash
     git checkout -b feature/your-feature
     ```
3. Commit your changes:
     ```bash
     git commit -m "Describe your feature"
     ```
4. Push your branch:
     ```bash
     git push origin feature/your-feature
     ```
5. Open a pull request for review.

## License

This project is licensed under the [MIT License](https://opensource.org/license/mit). See the LICENSE file for details.

## Contact

For questions, suggestions, or feedback, please contact:

- Satria Nur Saputro  
    [satrianursaputro06@gmail.com](mailto:satrianursaputro06@gmail.com)
