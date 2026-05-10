# Padel Game Analytics — Shot Classification System

## Project Overview

This project is a Computer Vision and Machine Learning based sports analytics system developed for analyzing padel gameplay videos. The system detects players and the ball, tracks ball movement, and classifies different types of shots such as Forehand, Backhand, and Smash.

The project demonstrates the practical implementation of:
- Object Detection
- Video Analytics
- Ball Tracking
- Shot Classification
- Sports AI Applications

---

# Features

- Player Detection using YOLOv8
- Ball Detection and Tracking
- Forehand / Backhand / Smash Classification
- Real-time Video Processing
- CSV Analytics Export
- Output Annotated Video Generation

---

# Technologies Used

- Python
- OpenCV
- YOLOv8 (Ultralytics)
- NumPy
- Pandas
- Google Colab

---

# Project Workflow

Input Video
↓
YOLO Object Detection
↓
Ball Tracking
↓
Shot Classification
↓
CSV Output + Annotated Video

---

# Output

## Generated Files

- `output_padel.mp4`
- `padel_shot_analysis.csv`

---

# Sample CSV Output

| frame | timestamp | shot_type |
|------|------------|------------|
| 285 | 11.4 | Smash |
| 585 | 23.4 | Forehand |
| 5255 | 210.2 | Backhand |

---

# Installation

```bash
pip install ultralytics opencv-python pandas numpy
