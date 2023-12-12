# EyeControlled_Mouse
This Python script utilizes computer vision and facial landmarks detection to control the mouse cursor based on eye movements.

<h1 align="center">👁️Mouse Event Handling</h1>

<p align="center">
  Control your mouse with the magic of your eyes! An interactive project using OpenCV, Mediapipe, and PyAutoGUI.
</p>

## 🚀 Features

- **Real-Time Eye Tracking**: Effortlessly control your mouse cursor in real-time.
- **Blink for Click**: A left-eye blink serves as a mouse click for a hands-free experience.

## 🌈 How It Works

Simply stare into the webcam, and watch as your eyes take control! Blink your left eye for a magical click.

## 🚨 Troubleshooting
Encountering issues? Let's troubleshoot:

💡 Ensure your webcam is connected and working.
💡 Double-check that the dependencies are installed correctly.


## 🎮 Usage
Look into the Webcam:
Move your eyes, see the magic happen!

Blink for Click:
A left-eye blink triggers a mouse click.

## Snapshots
It uses the OpenCV library to capture video from the default camera.
![Screenshot 2023-12-12 194304](https://github.com/suhelBhadane/EyeControlled_Mouse/assets/142994088/aaff1cd0-4ab0-438a-8405-9e63cb67d015)





It detects the landmarks x and y if face is present in front of screen
![Screenshot 2023-12-12 195241](https://github.com/suhelBhadane/EyeControlled_Mouse/assets/142994088/a43faa79-aa26-4833-a327-f9205484def6)


It face is not present then it shows none
![Screenshot 2023-12-12 195027](https://github.com/suhelBhadane/EyeControlled_Mouse/assets/142994088/1267d8dd-44c2-4d6a-8734-432cd28ae828)

It shows all the landmarks on the face
![Screenshot 2023-12-12 200727](https://github.com/suhelBhadane/EyeControlled_Mouse/assets/142994088/02fd566a-b191-4f63-940a-d548e9a0917e)

It shows that click is being made
![Screenshot 2023-12-12 201334](https://github.com/suhelBhadane/EyeControlled_Mouse/assets/142994088/2f295a01-fc63-477a-92ec-e5e920355708)



## ✨ Author
[Suhel Bhadane]

GitHub: https://github.com/suhelBhadane

Email: [suhelbhadane7666@gmail.com]

## 🛠️ Installation

 **Clone the Repository:**

   ```bash
   git clone https://github.com/suhelBhadane/EyeControlled_Mouse.git

To run your project, follow these steps:

1. Install Dependencies:
Ensure that you have the necessary dependencies installed by running the following command in your terminal or command prompt:

pip install opencv-python mediapipe pyautogui

2. Run the Script:
Open a terminal or command prompt in the directory where your script is located, and execute the following command:

python main.py











