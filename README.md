# NVX AI-Based Photoshop



<h3 align="center">🤖 An AI-Powered Web Application for Image Editing 🤖</h3>

<p align="center">
  A web-based image editor leveraging Mask R-CNN and OpenCV to provide advanced features like automatic background removal and image filtering.
</p>

<p align="center">
  <!-- Badges/Shields -->
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Flask-2.x-black?logo=flask" alt="Flask">
  <img src="https://img.shields.io/badge/TensorFlow-1.x-orange?logo=tensorflow" alt="TensorFlow">
  <img src="https://img.shields.io/badge/OpenCV-4.x-blue?logo=opencv" alt="OpenCV">
</p>

---

## About The Project

**AI-Based Photoshop** is a powerful yet simple web application that brings advanced image manipulation capabilities to your browser. Built with Flask, it uses a Mask R-CNN model with TensorFlow and OpenCV to perform complex tasks like automatic background removal. This project serves as an excellent demonstration of how modern AI techniques can be integrated into a user-friendly web service.

## ✨ Key Features

- ✅ **AI-Powered Background Removal:** Automatically detect and remove the background from images using a pre-trained Mask R-CNN model.
- ✅ **Image Enhancement Tools:** Apply various smoothing and filtering effects to improve photo quality.
- ✅ **Simple Web Interface:** An intuitive, browser-based UI for uploading images and applying edits.
- ✅ **Python Backend:** A lightweight and scalable backend powered by Flask.

## 🛠️ Tech Stack

- **Backend Framework:** [Flask](https://flask.palletsprojects.com/)
- **Machine Learning:** [TensorFlow](https://www.tensorflow.org/) 1.x, [Keras](https://keras.io/)
- **Computer Vision:** [OpenCV](https://opencv.org/)
- **AI Model:** [Mask R-CNN](https://github.com/matterport/Mask_RCNN) by Matterport
- **Language:** [Python](https://www.python.org/) 3.x

## 🚀 Getting Started

Follow these steps to get the project set up and running on your local machine.

### 1. Prerequisites

- Python 3.x
- pip (Python package installer)

### 2. Installation & Setup

1.  **Clone the repository:**

    ```
    git clone [this project]
    cd project
    ```

2.  **Create a Virtual Environment (Recommended):**

    ```bash
    python -m venv venv
    # On Windows
    venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3.  **Install Dependencies:**
    Install the required libraries from the `requirements.txt` file.

    ```bash
    pip install -r requirements.txt
    ```

    _Note: Ensure your environment meets the specific version requirements, especially `tensorflow==1.15` and `keras>2.0.6`._

4.  **Download Pre-trained Model Weights:**
    - Download the `mask_rcnn_coco.h5` file from the [Mask R-CNN GitHub releases page](https://github.com/matterport/Mask_RCNN/releases).
    - Place the downloaded `.h5` file into the root directory of the project.

### 3. Running the Application

Start the Flask development server:

```bash
python app.py
```

Open your web browser and navigate to `http://localhost:5000`. You can now upload an image and start editing!

## 🤝 Contributing

We welcome contributions! If you'd like to help improve the project:

1.  **Fork** the repository.
2.  Create your **Feature Branch** (`git checkout -b feature/AmazingAI-Feature`).
3.  **Commit** your changes (`git commit -m 'feat: Add some AmazingAI-Feature'`).
4.  **Push** to the Branch (`git push origin feature/AmazingAI-Feature`).
5.  Open a **Pull Request**.

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/license/mit). See the `LICENSE` file for more details.

## 📬 Contact

**Satria Nur Saputro**

- Email: [satrianursaputro06@gmail.com](mailto:satrianursaputro06@gmail.com)
- LinkedIn: [Satria Nur Saputro](https://id.linkedin.com/in/satrianursaputro)
- LinkedIn: [Nafi Ilham Hamami](https://id.linkedin.com/in/nafi-ilham-ha)
- LinkedIn: [Muhammad Iqbal Ainu Rafie](https://id.linkedin.com/in/ainurafie)
