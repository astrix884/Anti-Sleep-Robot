# Anti-Sleep-Robot
A DIY Robot with Face tracking + drowsiness detection + ESP32 water turret. An aggressive solution for exam season. 💦 🤖💦

Ever fallen asleep while studying?

Instead of fixing my sleep schedule, I built a robot that tracks my face, monitors my eyes, and sprays water whenever it detects drowsiness.

The project uses Python, OpenCV, MediaPipe, and ESP32 to perform real-time face tracking, eye monitoring, servo control, and water pump activation.

Perfect for students, makers, robotics enthusiasts, and anyone preparing for exams.

#installation
pip install opencv-python
pip install mediapipe
pip install pyserial

| Component         | ESP32 Pin  |
| ----------------- | ---------- |
| Pan Servo Signal  | GPIO 18    |
| Tilt Servo Signal | GPIO 19    |
| Relay IN          | GPIO 23    |
| GND               | Common GND |
| 5V (Relay)        | 5V/VIN     |



| Servo Wire    | Connection  |
| ------------- | ----------- |
| Brown/Black   | GND         |
| Red           | External 5V |
| Orange/Yellow | GPIO18      |

| Servo Wire    | Connection  |
| ------------- | ----------- |
| Brown/Black   | GND         |
| Red           | External 5V |
| Orange/Yellow | GPIO19      |

| Relay Pin | ESP32  |
| --------- | ------ |
| IN        | GPIO23 |
| VCC       | 5V     |
| GND       | GND    |
