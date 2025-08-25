# ✋ Virtual Gesture Keyboard

A hand gesture–controlled virtual keyboard built using OpenCV, MediaPipe, and Python.
This project allows you to type on a virtual keyboard by simply pinching your thumb and index finger over a key on the screen — no physical keyboard required!

## 🚀 Features

- 🖐️ Hand Tracking – Detects and tracks your hand using MediaPipe Hands

- 🎹 Virtual Keyboard – On-screen QWERTY keyboard with numbers, alphabets, and special keys.

- ✍️ Typing via Pinch Gesture – Pinch index and thumb to "press" a key.

- 🔠 Caps/Shift Toggle – Switch between uppercase and lowercase.

- ⌫ Backspace, Space, Enter, and Clear – Special functional keys included.

- 📄 Text Box Overlay – Shows typed text at the top of the screen (supports multiline).

- 🎨 Modern UI – Semi-transparent keys, highlight effects, and smooth typing box.

## 🛠️ Tech Stack

- Python 3.8+
- OpenCV– Computer vision & rendering
- MediaPipe– Hand landmark detection
- NumPy – Array calculations
- Math & Time modules – Distance calculation & click delay logic

## 📂 Project Structure
    ├── gesture_keyboard.py    # Main Python script
    ├── README.md              # Project documentation
    └── requirements.txt       # Dependencies (optional)


## ⚙️ Installation & Setup
1. Clone the repository

        git clone https://github.com/yourusername/gesture-keyboard.git
        cd gesture-keyboard

2. Create virtual environment (optional but recommended)

        python -m venv venv
        source venv/bin/activate    # On Linux/Mac
        venv\Scripts\activate       # On Windows

3. Install dependencies

        pip install opencv-python mediapipe numpy

4. Run the project

        python gesture_keyboard.py # if using a .py file
        else run the ipynb cell to run the project.


## 🎮 How to Use

- Launch the program – a webcam window will open.
- A virtual keyboard appears at the bottom of the screen.
- Place your hand in front of the camera.
- Move your index finger over a key.
- Pinch your thumb and index finger to press the key.
- Typed text will appear in the text box at the top.
- Use BACK, CLEAR, SHIFT, ENTER, SPACE for normal typing controls.
- Press ESC to exit the program.

## 🔑 Controls

- Pinch Gesture → Press selected key
- SHIFT → Toggle Caps / Lowercase
- BACK → Delete last character
- SPACE → Insert space
- ENTER → Newline
- CLEAR → Clear all text
- ESC Key → Exit

## 📌 Future Improvements

- ✅ Add multiple language support (Hindi, Spanish, etc.)
- ✅ Word suggestions / auto-complete
- ✅ Customizable keyboard layouts
- ✅ Voice output for typed text

## 🤝 Contributing

- Contributions are welcome! If you’d like to improve this project:
- Fork the repo
- Create your feature branch (git checkout -b feature-name)
- Commit changes (git commit -m "Added feature")
- Push to branch (git push origin feature-name)
- Open a Pull Request

### Made with ❤️ by Akshansh Roy
