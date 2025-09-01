# 🤟 Hand Sign Recognizer by Andrew

A real-time American Sign Language (ASL) alphabet recognition system using AI and computer vision.

![Hand Sign Recognizer](https://img.shields.io/badge/Status-Demo%20Available-brightgreen)
![Python](https://img.shields.io/badge/Python-3.11+-blue)
![Flask](https://img.shields.io/badge/Flask-3.1.2-red)
![OpenCV](https://img.shields.io/badge/OpenCV-4.8.1-orange)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0.10.7-purple)

## 🌐 Live Demo

**📱 [View Live Demo on GitHub Pages](https://yourusername.github.io/hand-sign-recognizer/)**

*Note: The live demo shows the interface and features. For full camera functionality, download and run locally.*

## ✨ Features

- **Real-time ASL Recognition**: Recognizes all 26 ASL alphabet signs
- **Live Camera Feed**: Real-time video processing with hand detection
- **Interactive Controls**: Switch between predict and record modes
- **Word Building**: Build words by combining recognized letters
- **Mobile Responsive**: Works perfectly on phones and tablets
- **Debug Information**: Real-time system status and metrics
- **Training Mode**: Collect and train custom data
- **Professional UI**: Beautiful, modern interface

## 🚀 Quick Start

### Option 1: Try the Demo
1. Visit the [live demo](https://yourusername.github.io/hand-sign-recognizer/)
2. Explore the interface and features
3. See how the application works

### Option 2: Run Locally (Full Functionality)

#### Prerequisites
- Python 3.11 or higher
- Webcam
- Good lighting

#### Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/hand-sign-recognizer.git
cd hand-sign-recognizer

# Create virtual environment
python -m venv .venv

# Activate virtual environment
# On Windows:
.venv\Scripts\activate
# On macOS/Linux:
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

#### Run the Application
```bash
# Start the web application
python web_app.py

# Open your browser and go to:
# http://localhost:5000
```

## 📱 How to Use

1. **Camera Setup**: Ensure good lighting and your hand is clearly visible
2. **Predict Mode**: Show ASL alphabet signs to see real-time recognition
3. **Record Mode**: Collect training data for custom signs
4. **Build Words**: Use spacebar to add letters and build words
5. **Controls**: Use the buttons or keyboard shortcuts (R, P, T, C)

### Keyboard Shortcuts
- `R` - Switch to Record mode
- `P` - Switch to Predict mode  
- `T` - Train model
- `C` - Clear current word
- `Space` - Add current prediction to word
- `Backspace` - Remove last letter

## 🛠️ Technology Stack

- **Backend**: Python, Flask, OpenCV, MediaPipe
- **AI/ML**: Scikit-learn, KNN algorithm
- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
- **Real-time**: Server-Sent Events (SSE)
- **Deployment**: GitHub Pages, GitHub Actions

## 📁 Project Structure

```
hand-sign-recognizer/
├── index.html                 # GitHub Pages demo
├── web_app.py                 # Main Flask application
├── app.py                     # Desktop application
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation
├── README_GITHUB.md          # GitHub-specific README
├── .github/workflows/        # GitHub Actions
│   └── deploy.yml            # Auto-deployment workflow
├── templates/                # Flask templates
│   └── index.html           # Full application template
├── models/                   # Trained models
│   └── knn_asl.joblib       # KNN model
├── dataset/                  # Training data
│   ├── A/                   # Letter A samples
│   ├── B/                   # Letter B samples
│   └── ...                  # All 26 letters
└── dist/                    # Distribution files
```

## 🎯 Features in Detail

### Real-time Recognition
- **MediaPipe Hand Detection**: Accurate hand landmark detection
- **KNN Classification**: Fast and reliable letter recognition
- **Live Video Processing**: Real-time frame analysis
- **Confidence Scoring**: Shows recognition confidence levels

### User Interface
- **Responsive Design**: Works on all devices
- **Live Metrics**: FPS, confidence, accuracy, duration
- **Status Indicators**: Real-time system status
- **Debug Panel**: Technical information and troubleshooting

### Training System
- **Data Collection**: Record custom training samples
- **Model Training**: Train on your own data
- **Progress Tracking**: Visual training progress
- **Sample Management**: Organize training data

## 🌐 Deployment Options

### GitHub Pages (Demo)
- ✅ Static demo version
- ✅ No server required
- ✅ Automatic deployment
- ❌ No camera functionality

### Local Development
- ✅ Full functionality
- ✅ Camera access
- ✅ Real-time processing
- ✅ Training capabilities

### Cloud Deployment
- ✅ Full functionality
- ✅ Accessible anywhere
- ✅ Scalable
- ⚠️ Requires server setup

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **MediaPipe**: Hand landmark detection
- **OpenCV**: Computer vision processing
- **Bootstrap**: UI framework
- **Font Awesome**: Icons
- **Andrew**: Original developer

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/yourusername/hand-sign-recognizer/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/hand-sign-recognizer/discussions)
- **Email**: your.email@example.com

## 🔗 Links

- **Live Demo**: [https://yourusername.github.io/hand-sign-recognizer/](https://yourusername.github.io/hand-sign-recognizer/)
- **Repository**: [https://github.com/yourusername/hand-sign-recognizer](https://github.com/yourusername/hand-sign-recognizer)
- **Documentation**: [Full README](README.md)

---

**⭐ Star this repository if you find it helpful!**

**🤟 Made with ❤️ by Andrew**
