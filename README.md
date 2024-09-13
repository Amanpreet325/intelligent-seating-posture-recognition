
# Smart Posture Detection System

## Overview
This project uses deep learning to detect human postures (e.g., folding hands, kneeling, sitting) in real-time using key point detection. It leverages **TensorFlow**, **Keras**, **OpenCV**, and **OpenPose** for posture recognition.

## Features
- Detects hand-folding, kneeling, and sitting postures
- Real-time processing using OpenPose for key point extraction
- Built with Python-based algorithms for posture analysis
  ![image](https://github.com/user-attachments/assets/ab05e546-8587-4aa3-a066-d813685414bc)

![s111](https://github.com/user-attachments/assets/ae99c9c7-0bd4-4f13-a9f4-fe3074fdc074)

## Technologies
- **TensorFlow**
- **Keras**
- **OpenCV**
- **OpenPose (CMU)**

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/smart-posture-detection.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the system:
```bash
python posture_detection.py
```

## Posture Detection Methods
- **Folding Hands**: Calculates distances between arm key points.
- **Kneeling Down**: Measures angles between hip and ankle.
- **Sitting on a Chair**: Analyzes the position of the hips relative to other points.

---

