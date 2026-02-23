# GlucoSense – Smart Non-Invasive Glucose Monitoring System

## Project Overview
GlucoSense is a smart, non-invasive glucose monitoring system designed to estimate blood glucose levels without painful finger-pricking. The system uses an **infrared (IR) sensor**, an **amplification circuit**, and an **ultrasonic sensor** to measure finger thickness. Data from the sensors is processed using a **neural network-based deep learning model** to predict blood glucose levels accurately and reliably.

---

## Technologies Used

### Hardware
- IR Sender and IR Receiver
- Amplification Circuit
- Arduino Nano
- Ultrasonic Sensor (for finger thickness measurement)

### Software
- Arduino IDE (C/C++)
- Python (TensorFlow/Keras for neural network training, Pandas, NumPy, scikit-learn, Matplotlib, Seaborn, ReportLab)
- Fritzing (for circuit design)

---

## Functional Highlights
- Non-invasive blood glucose estimation using IR and ultrasonic sensors
- Signal amplification and acquisition via Arduino Nano
- Preprocessing and prediction using a trained neural network model
- Supports generation of detailed PDF glucose reports
- System tested for robustness against ambient light variations

---

## Future Enhancements
- Incorporation of additional skin parameters (color, texture) using camera modules
- Cloud storage for historical glucose tracking
- Integration with healthcare systems for remote monitoring
- Enhanced neural network accuracy with larger, diverse datasets

---

## Handover / Takeover (HOTO)
- Complete source code and documentation included
- Neural network model and training notebooks provided
- Circuit diagrams, block diagrams, and workflow flowcharts available
- Project ready for further development, research, or commercial adaptation

---

## Installation Instructions

### Arduino
1. Open `main.ino` from `Arduino_Code/`
2. Upload to Arduino Nano using Arduino IDE
3. Connect IR and ultrasonic sensors according to circuit diagram
4. Verify readings via Serial Monitor

### Python Neural Network
1. Install required packages:
```bash
   pip install numpy pandas scikit-learn tensorflow matplotlib seaborn reportlab
```
2. Run `model_training.ipynb` to retrain the neural network or use the provided trained model

---

## Team Members
| Name | Student ID |
|------|------------|
| Aiman Malik | 2021-CE-23 |
| Ayesha | 2021-CE-18 |
| Samreen Razzaq | 2021-CE-13 |
| Urwah Imran | 2021-CE-15 |

---

## Supervisors
- **Dr. Yasir Saleem**
- **Engr. Afeef Obaid** (Co-supervisor)

---

## License
This project is intended for academic and research purposes only. For reuse or extension, contact the team or the Department of Computer Engineering at UET Lahore.