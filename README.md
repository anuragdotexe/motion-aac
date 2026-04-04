# 📱 Motion-to-Speech (AAC)

A specialized communication tool designed for individuals with motor or speech challenges. This web-based application uses a smartphone's internal **accelerometer** to translate physical tilts into clear, audible speech.

## 🌟 Key Features
- **Smart Motion Filtering:** Uses a Low-Pass Filter to ignore hand tremors and jitters.
- **Return-to-Center Logic:** Prevents accidental repeated speech by requiring the phone to return to a "Flat" position between phrases.
- **Voice Feedback:** Uses the Web Speech API for high-quality, offline text-to-speech.
- **Visual Feedback:** Real-time X/Y coordinate display and system status indicators.

## 🛠 How It Works
The app maps the 3D orientation of the phone to specific phrases:
| Motion | Resulting Speech |
| :--- | :--- |
| **Tilt Left (X-Axis)** | "No" |
| **Tilt Right (X-Axis)** | "Yes" |
| **Tilt Forward (Y-Axis)** | "Sure" |
| **Tilt Backward (Y-Axis)** | "Why?" |



## 🚀 Getting Started

### Prerequisites
- A modern smartphone (Android or iOS).
- A browser that supports the Device Orientation API (Chrome, Safari, Firefox).
- **HTTPS is required** for sensor access.

### Local Development (VS Code)
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
