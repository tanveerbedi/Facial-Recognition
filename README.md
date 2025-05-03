# Facial Recognition System

A simple real-time facial recognition system using OpenCV's Haar Cascade Classifier for face detection. This project captures video from your webcam, detects faces in each frame, and displays a bounding box around each detected face.

---

## 📚 Features

* Real-time face detection
* Uses Haar Cascade Classifier
* Webcam integration with OpenCV

---

## 📊 Tech Stack

* **Python 3.x**
* **OpenCV (cv2)**

---

## 📁 Installation

1. **Clone the repository:**

   ```bash
   https://github.com/tanveerbedi/Facial-Recognition
   ```

2. **Install dependencies:**

   ```bash
   pip install opencv-python
   ```

3. **Download the Haar Cascade XML:**

   * Make sure the `haarcascade_frontalface_default.xml` file is in your working directory.
   * You can download it from [OpenCV GitHub](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)

---

## 🚀 How to Run

1. Ensure your webcam is connected and functional.
2. Run the script:

   ```bash
   python facial_recognition.py
   ```
3. Press `ESC` to close the window and exit the program.

---

## ⚠️ Troubleshooting

* **Blank Screen / No Face Detected:**

  * Ensure `haarcascade_frontalface_default.xml` file is correctly named and placed in the directory.
  * Check your webcam driver or permissions.

* **Error in Classifier Path:**

  * Double-check the filename: remove extra spaces from `'haarcascade_frontalface_default .xml'` — it should be `'haarcascade_frontalface_default.xml'`.

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👥 Author

**Tanveer Singh Bedi**
GitHub: [@tanveerbedi]

---

## 📃 Acknowledgements

* OpenCV Documentation and Haar Cascade Classifier
* Real-time computer vision resources
