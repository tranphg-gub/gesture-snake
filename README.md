# Gesture-Controlled Snake Game

A modern Snake game controlled by hand gestures using MediaPipe and IoT technology. Control the snake with your hand movements (up, down, left, right) detected through your webcam.

## Features

- 🎮 Classic Snake game mechanics
- 👋 Hand gesture recognition using MediaPipe
- 🌐 Web-based interface
- 📱 Real-time gesture detection
- 🎯 Score tracking
- 🔄 WebSocket real-time communication

## Requirements

- Python 3.8+
- Webcam
- Modern web browser

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/tranphg-gub/gesture-snake.git
cd gesture-snake
```

### 2. Install Python dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the server
```bash
python app.py
```

### 4. Open in browser
Open your browser and go to: `http://localhost:5000`

## How to Play

1. **Allow webcam access** when prompted
2. **Hand gestures:**
   - ☝️ **Thumb up** = Move snake UP
   - 👎 **Thumb down** = Move snake DOWN
   - 👈 **Thumb left** = Move snake LEFT
   - 👉 **Thumb right** = Move snake RIGHT
3. **Eat food** to grow your snake
4. **Avoid walls and yourself** to stay alive
5. Your **score increases** with each food eaten

## Project Structure

```
gesture-snake/
├── app.py                 # Flask server & gesture detection
├── requirements.txt       # Python dependencies
├── static/
│   ├── index.html        # Game interface
│   ├── style.css         # Game styling
│   └── game.js           # Game logic & WebSocket
└── README.md             # This file
```

## Technologies Used

- **Python**: Backend & gesture recognition
- **Flask**: Web framework
- **MediaPipe**: Hand gesture detection
- **OpenCV**: Video processing
- **WebSocket**: Real-time communication
- **HTML/CSS/JavaScript**: Frontend

## License

MIT License