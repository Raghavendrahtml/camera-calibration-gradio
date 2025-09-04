# Camera Calibration (OpenCV + Gradio)

This project calibrates a camera using OpenCV, with a Gradio user interface for uploading calibration images, running calibration, and visualizing results.

## Setup
- Open in **Google Colab**.
- Run the first cell to install packages.
- Upload calibration images (≥15 JPEGs of 9×6 chessboard).

## Usage
1. Tab **1) Upload** → upload calibration images.  
2. Tab **2) Calibrate** → run calibration (results saved to `calibration.json`).  
3. Tab **3) Visualize** → see camera poses, overlays, and undistortion preview.  

## Outputs
- `calibration.json` → intrinsics, distortion, extrinsics.  
- `/out/camera_poses.png` → 3D plot of estimated camera poses.  
- `/out/overlay_*.jpg` → overlays with chessboard + axes.  
- `/out/undistort_preview.jpg` → before/after lens distortion correction.  

## Authors
- Raghavendra Huliyurdurga MAllesha
- Akhilesh Katari
