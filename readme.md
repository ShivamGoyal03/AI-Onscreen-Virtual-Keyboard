# Virtual Keyboard

This project is a virtual keyboard implemented in Python using the OpenCV, Mediapipe, and PyAutoGUI libraries. 

It was created by [Shivam (21CSU090)](https://github.com/ShivamGoyal03) and [Saransh Shukla (21CSU461)](https://github.com/saransh-2021) using Python and computer vision techniques.

## Description

The virtual keyboard allows you to type on your computer using your fingers. It uses the Mediapipe library to detect hand landmarks and the PyAutoGUI library to simulate key presses. The project demonstrates the use of computer vision to create an interactive user interface.

## Functionalities

- Hand detection: The program uses the Mediapipe library to detect the user's hand and track the movement of the fingers.
- Key press simulation: The program uses the PyAutoGUI library to simulate key presses based on the user's finger movements.
- Interactive user interface: The program displays a virtual keyboard that the user can interact with.

## Installation

To run this project, you need to have Python installed on your computer. You also need to install the following Python libraries:

- OpenCV: `pip install opencv-python`
- Mediapipe: `pip install mediapipe`
- PyAutoGUI: `pip install pyautogui`

**OR**

```
pip install -r requirements.txt
```

## Usage

To use the virtual keyboard, run the `main.ipynb` file. This will open a window showing a virtual keyboard and your hand. You can type on the virtual keyboard by moving your index finger over the keys.

## License

This project is licensed under the MIT License.
