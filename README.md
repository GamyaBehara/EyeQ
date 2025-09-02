# 🧠 EyeQ: Image Object Detection Brain

EyeQ is a computer vision project that acts like a simple **visual brain**.  
It mimics the way humans look at an image and instantly recognize the objects inside.  
Using state-of-the-art deep learning, EyeQ can scan any picture and tell you **what objects are present**.

---

## 🔹 What does it do?
- Accepts an image as input.  
- Analyzes the image using an object detection model.  
- Outputs:
  - A **list of detected objects** (e.g., `person, chair, laptop`).  
  - (Optional) An **annotated image** with bounding boxes around each detected object.  

**Example:**  
- Input: Photo of a classroom  
- Output: `[person, chair, bench, tvmonitor]`

---

## 🔹 Why use a pre-trained model?
Training an object detection model from scratch requires:
- Millions of labeled images  
- Very high computing power (GPUs for weeks)  
- Expertise in deep learning model design  

Instead, EyeQ leverages **YOLOv5 (You Only Look Once v5)**, a pre-trained object detection model:
- Already trained on the **COCO dataset** (80+ common everyday objects).  
- Provides **fast and accurate predictions** out-of-the-box.  
- Saves **time, resources, and effort** while achieving state-of-the-art results.  

---

## 🛠️ Tech Stack
- **Python**  
- **YOLOv5** (PyTorch)  
- **OpenCV** (for image handling and visualization)  
- **COCO Dataset** (for pre-trained object classes)  

---

## 🚀 Workflow
1. **Input:** User provides an image.  
2. **Processing:** YOLOv5 analyzes the image and detects objects.  
3. **Output:**  
   - A list of object names.  
   - Optional annotated image with bounding boxes.  

---
## Application Screenshots
<img width="427" height="886" alt="Screenshot 2025-08-31 194428" src="https://github.com/user-attachments/assets/3ead61cd-ac82-41c1-a5c4-658d15858451" />

<img width="427" height="886" alt="Screenshot 2025-08-31 194441" src="https://github.com/user-attachments/assets/01064110-e975-4b64-8f47-67c774584943" />

<img width="427" height="886" alt="Screenshot 2025-08-31 194453" src="https://github.com/user-attachments/assets/e3b63324-0c5a-4e9e-896e-02e7f8c51805" />



## 📌 Future Improvements
- Extend support to **video streams** (real-time detection).  
- Add **object counting** and category-based filtering.  
- Build a **web app** or **mobile app** interface.  
- Explore custom training for domain-specific objects.  

---

👩‍💻 **Developed by:** [Your Name]  
📌 Project: EyeQ – Image Object Detection Brain
