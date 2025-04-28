# 🦴 Bone Fracture Detection using YOLOv11

A deep learning-based computer vision system to automatically detect bone fractures from medical images using the YOLOv11 object detection model.

---
# ![image](https://github.com/user-attachments/assets/597d9b10-1fa5-479a-9f6d-6a2fd9ae26a6)
# ![image](https://github.com/user-attachments/assets/5dd183bb-16d7-4fa8-8043-f2b5f99ad309)
# ![image](https://github.com/user-attachments/assets/4a7fcfd5-7624-4111-826b-3282f08c0719)
# ![image](https://github.com/user-attachments/assets/6aa5d38f-e010-4397-8c51-458dd6e70055)
# ![image](https://github.com/user-attachments/assets/038a6b3e-bb22-437a-b931-05a8021946ce)




## 🚀 Project Overview

This project focuses on applying state-of-the-art object detection techniques to assist in the early detection of bone fractures. By leveraging YOLOv11, the system can localize and identify fractures in X-ray or medical imaging data with high precision and speed.

---

## 📚 Objectives

- Develop a robust bone fracture detection model using YOLOv11.
- Train and validate the model on a labeled medical image dataset.
- Achieve fast and accurate fracture localization to assist healthcare professionals.
- Deploy the trained model for real-world inference on unseen medical images.

---

## 🛠 Technologies and Tools Used

- Python 3.x
- YOLOv11
- PyTorch / Ultralytics
- OpenCV
- NumPy
- Matplotlib
- LabelImg (for annotation)

---

## 🧠 Dataset

- Medical X-ray images of bones (including fractured and non-fractured samples).
- Bounding box annotations marking fracture locations.
- (Custom/prepared dataset based on project needs.)

---

## 🏗️ Project Structure


---

## ⚙️ How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/bone-fracture-detection-yolov11.git
   cd bone-fracture-detection-yolov11
```

### nstall required dependencies:
```
pip install -r requirements.txt
```

```
### Train the model:
```
yolo task=detect mode=train model=yolov11.yaml data=yolov11_custom.yaml epochs=100 imgsz=416 batch=16

```
### Run inference
```
yolo task=detect mode=predict model=runs/detect/train/weights/best.pt source=your_test_image_folder


```
### 📈 Results and Evaluation
- Achieved high accuracy in detecting fracture regions.
- Visual bounding box predictions overlaid on input X-ray images.
- Model optimized for both accuracy and real-time inference.

### Future Improvements
- Integrate with clinical diagnosis systems.
- Extend the model to classify types of fractures.
- Explore multi-modal datasets (e.g., combining CT scans with X-rays).


---

## License
This repository is licensed under the MIT License. Feel free to use and modify the code as needed.

---

## Author
**Md. Rasel Sarker**  
Email: [rasel.sarker6933@gmail.com](mailto:rasel.sarker6933@gmail.com)  

<br>
<h1 align="left">
 <h2><img src = "https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width=30px valign="bottom"> 🌐 Connect with Me:</h2>
</h1>

<p align="center">
  <a href="mailto:rasel.sarker6933@gmail.com"><img src="https://img.shields.io/badge/Email-rasel.sarker6933@gmail.com-blue?style=flat-square&logo=gmail"></a>
  <a href="https://github.com/raselsarker69"><img src="https://img.shields.io/badge/GitHub-%40Raselsarker-lightgrey?style=flat-square&logo=github"></a>
  <a href="https://www.linkedin.com/in/rasel-sarker-405160227/"><img src="https://img.shields.io/badge/LinkedIn-Rasel%20Sarker-blue?style=flat-square&logo=linkedin"></a>
  <a href="https://www.facebook.com/mdrasel.sarker.7773631"><img src="https://img.shields.io/badge/Facebook-%40Raselsarker-blue?style=flat-square&logo=facebook"></a>
  <a href="https://www.kaggle.com/mdraselsarker"><img src="https://img.shields.io/badge/Kaggle-%40Raselsarker-blue?style=flat-square&logo=kaggle"></a>
  <a href="https://www.youtube.com/@raselsarker69"><img src="https://img.shields.io/badge/YouTube-Rasel%20Sarker-red?style=flat-square&logo=youtube"></a>
  <a href="https://www.facebook.com/groups/832585175685301"><img src="https://img.shields.io/badge/Facebook%20Group-Rasel%20Sarker%20Group-blue?style=flat-square&logo=facebook"></a>
  <br>
  <img src="https://img.shields.io/badge/Phone-%2B8801581528651-green?style=flat-square&logo=whatsapp">
</p>
 

---

<div align="center">

Thank you for visiting my repository. I hope these projects inspire and guide your learning journey!

---

Feel free to explore, learn, and build upon these projects. Happy coding!<br>

&copy; 2025 Computer vision Projects

</div>
