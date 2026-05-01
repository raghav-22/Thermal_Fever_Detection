# 🔥 Thermal Face Detection using OpenCV

This project simulates a **thermal imaging system** using a regular webcam. It detects faces and estimates their temperature using image processing techniques.

---

## 🚀 Features

* Real-time webcam processing
* Face detection using Haar Cascade
* Thermal heatmap visualization
* Simulated temperature estimation
* Automatic image capture for high temperature

---

## 🧠 How It Works

1. Webcam frame is captured
2. Frame is converted into a **heatmap**
3. Face is detected using Haar Cascade
4. Pixel intensity is converted into temperature
5. Temperature is displayed on screen
6. If temperature exceeds threshold:

   * Image is captured
   * Face is saved separately

---

## 🛠️ Tech Stack

* Python
* OpenCV
* NumPy

---

## 📦 Installation

```bash
git clone https://github.com/raghav-22/Thermal_Fever_Detection.git
cd Thermal_Fever_Detection
pip install opencv-python numpy
```

---

## ▶️ Usage

```bash
face_temperature_capture.ipynb
```

Press **q** to exit the application.

---

## ⚙️ Configuration

You can adjust:

```python
TEMP_TUNER = 1.5
TEMP_TOLERENCE = 70.6
```

* `TEMP_TUNER` → Controls temperature scaling
* `TEMP_TOLERENCE` → Threshold for alerts

---

## 📁 Output

* `image.jpg` → Captured frame
* `face.jpg` → Detected face

---

## ⚠️ Disclaimer

This project does **NOT use a real thermal camera**.
Temperature values are **simulated** and should not be used for medical or safety purposes.

---

## 📌 Limitations

* Not accurate for real temperature measurement
* Sensitive to lighting conditions
* Haar Cascade is not robust for all face angles

---

## 📄 License

MIT License
