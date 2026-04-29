# 📸 Image Capture and Video Processing Using OpenCV

## 🎯 Aim

To develop a Python program using OpenCV to capture images from a webcam and perform real-time video processing operations such as displaying, resizing, and rotating frames.

---

## 🛠️ Technologies Used

* Python 3.x
* OpenCV (`cv2`)
* Matplotlib
* Jupyter Notebook / VS Code

---

## 📌 Features

* Capture image from webcam
* Save captured frame as JPG file
* Display live video stream
* Resize video frames (640 × 480)
* Rotate video frames (90° clockwise)

---

## ⚙️ Installation

```bash
pip install opencv-python matplotlib
```

---

## 🚀 How to Run

1. Open Jupyter Notebook
2. Run cells step-by-step
3. Allow camera access
4. Execute each section:

   * Capture image
   * Display video
   * Resize video
   * Rotate video

---

## 🧠 Algorithm

1. Import required libraries
2. Initialize webcam using `cv2.VideoCapture(0)`
3. Capture frame using `cap.read()`
4. Save frame using `cv2.imwrite()`
5. Convert BGR → RGB for display
6. Display using Matplotlib
7. Resize frame using `cv2.resize()`
8. Rotate frame using `cv2.rotate()`
9. Release camera using `cap.release()`

---

## 📷 Output

### 1️⃣ Captured Image
<img width="583" height="456" alt="image" src="https://github.com/user-attachments/assets/b8890151-5afc-43e9-a1f5-c8517ed20c15" />


### 2️⃣ Live Video Display

<img width="546" height="466" alt="image" src="https://github.com/user-attachments/assets/8f94efa5-0393-4d53-a390-06610cdf2bda" />


### 3️⃣ Resized Video

<img width="557" height="458" alt="image" src="https://github.com/user-attachments/assets/d7b6db0f-492a-4bde-bf96-4da1bc12aae3" />

### 4️⃣ Rotated Video


<img width="327" height="451" alt="image" src="https://github.com/user-attachments/assets/ac83d0d9-2505-45ca-8a40-ca829b4ce759" />


---

## 📊 Result

The program successfully captures images from the webcam and performs real-time video processing operations including display, resizing, and rotation using OpenCV.

