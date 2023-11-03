# Body PoseGaming: Pose-Based Motion Gaming Application

Body PoseGaming is a motion-based gaming application that utilizes real-time pose and hand detection through a webcam, allowing users to control in-game characters using body movements and gestures. This interactive gaming experience is made possible by the integration of the MediaPipe library for accurate pose and hand recognition and PyAutoGUI for simulating keyboard events. With Body PoseGaming, users can immerse themselves in games by moving, jumping, crouching, and performing various gestures, all detected in real-time.

**Key Features**

- **Real-Time Pose Detection:** Detects the user's body pose, including key landmarks such as shoulders and wrists, utilizing the MediaPipe library.
  
- **Hand Gesture Recognition:** Analyzes hand positions to distinguish between joined and apart hands, enabling specific in-game actions.
  
- **Gesture-Based Control:** Enables users to control the game in real-time by moving left, right, jumping, crouching, or performing various gestures.
  
- **Easy Integration:** Seamlessly integrates with existing games and applications, offering a unique and intuitive way to interact with digital environments.

**How it Works**

- **Pose Detection:** Utilizes the MediaPipe library to analyze the user's real-time body pose. Landmark identification determines postures like standing, jumping, or crouching.

- **Hand Gesture Recognition:** Analyzes hand positions and proximity to recognize gestures. For example, joined hands trigger specific commands (e.g., firing in a shooting game).

- **Game Control:** Maps detected poses and gestures to corresponding keyboard events ('left,' 'right,' 'up,' 'down,' 'space'), providing intuitive game control for users.

## Getting Started

1. Clone the repository to your local machine:
git clone https://github.com/SheikhMohammedSakhib/Body-PoseGaming.git

2. Install the required Python libraries using `pip`:
pip install opencv-python pyautogui mediapipe matplotlib

3. **Open your preferred online game website (e.g., Subway Surfers) and start the game:**
- Typically controlled with 'up,' 'down,' 'left,' and 'right' keys, but with this setup, your body movements, detected by the code, will control the game.

3. Run the code
4. Position yourself in front of the webcam.
5. Join your hands to initiate the game.
6. Move, jump, or crouch to control the game characters.
7. Press 'Esc' to exit the game.




