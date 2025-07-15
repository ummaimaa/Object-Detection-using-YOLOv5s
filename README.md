# Object-Detection-using-YOLOv5s

This project demonstrates how to use the **YOLOv5 object detection model** (pre-trained on the COCO dataset) using PyTorch and Torch Hub. The workflow includes:

- Detecting and filtering specific object classes (e.g., person, car, dog)
- Counting object classes in traffic images
- Analyzing the impact of confidence thresholds on detection count
- Visualizing results and exporting to CSV/PNG

---

##  Features

- Load pretrained YOLOv5s from Torch Hub
- Detect objects in any image
- Filter results by specific COCO classes
- Count and save object occurrences
- Analyze detection count across multiple confidence thresholds
- Save predictions as images and structured data

---

##  Dependencies

Install the required packages:

```bash
pip install torch torchvision pandas matplotlib pillow
