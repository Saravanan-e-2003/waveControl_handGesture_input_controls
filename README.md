# Hand Gesture Control System

This project utilizes [MediaPipe](https://ai.google.dev/edge/mediapipe/solutions/guide) and Python to create a highly customizable hand gesture control system. With simple hand gestures, users can control the brightness and volume of their PC. The system can be extended to include additional controls and features.

## Features
- **Hand Gesture Controls**: Control brightness and volume with hand gestures.
- **Customizable**: Easily switch between modes or create new ones.
- **Modular Design**: Add other controls by modifying or expanding the `changing_mods_template.py`.

## How It Works
Using the MediaPipe library, the system detects hand gestures through the camera. Specific gestures are mapped to actions like adjusting the volume or brightness. The gesture recognition is processed in real time, allowing for smooth control of your PC without the need for physical interaction.

## Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Saravanan-e-2003/waveControl_handGesture_input_controls.git
    ```
2. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Run the system**:
    ```bash
    python changing_mods_template.py
    ```

## Changing Modes
To switch between control modes, use the `changing_mods_template.py` script. You can customize or add new modes by editing this script:
```bash
python changing_mods_template.py
