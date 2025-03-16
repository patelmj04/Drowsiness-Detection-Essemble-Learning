# Drowsiness Detection System

A real-time drowsiness detection application built with Python, OpenCV, TensorFlow, and Tkinter. It uses a pre-trained CNN model to classify eye states (open/closed) and alerts the user when drowsiness is detected.

## Features
- **Model Training**: Trains a CNN on an eye state dataset.
- **Live Detection**: Detects faces and eyes via webcam, monitors eye states, and triggers alerts.
- **User Interface**: Displays video feed, status, model accuracy, and control buttons.

## Requirements
- Python 3.x
- Dependencies:
  ```
  pip install opencv-python numpy tensorflow pillow scikit-learn
  ```

## Dataset
- Path: `D:\Users\Home_Desktop\Desktop\Mj\PROJECTS\Drowsiness-Detection-Essemble-Learning\eye_dataset`
- Structure:
  ```
  eye_dataset/
  ├── open/
  │   ├── img1.jpg
  │   └── ...
  ├── closed/
  │   ├── img1.jpg
  │   └── ...
  ```

## Usage
1. **Install dependencies** (see above).
2. **Run the script**:
   ```bash
   python drowsiness_detection.py
   ```
3. **Train Model**:
   - Click "Train Model" to train the eye state classifier.
4. **Start Detection**:
   - Click "Start Detection" for live testing (requires a webcam).
5. **Stop Detection**:
   - Click "Stop Detection" to pause.

## Output
- Model saved as `eye_state_model.h5`.
- UI shows live feed, status (Inactive/Alert/Drowsy), and model accuracy.

## Notes
- Ensure the dataset path is correct and contains valid images.
- Adjust `epochs` in the code for better model accuracy if needed.

## License
MIT License

---

Save this as `README.md` in your project directory. Let me know if you’d like to expand it!
