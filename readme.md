✍️ Handwritten Digit Recognition
🧠 Project Overview

This is an interactive web application that allows users to draw a digit on a canvas, and the trained model will predict the digit in real-time. Additionally, you can visualize the prediction process in 3D, showcasing intermediate layer outputs of the neural network.

Live Demo

Check out the live demo of this project here: https://handwritten-digit-recognition-fk9jderuo.vercel.app

🚀 Getting Started

Prerequisites
Download and install Node.js
Setup Instructions
# Install dependencies (only needed the first time)
npm install

# Start the development server (runs on localhost:8080)
npm run dev

# Build for production (output in the dist/ directory)
npm run build
🖱️ How to Use

Draw a single digit (0–9) on the canvas.
The model will automatically predict the digit.
Click on “Visualize in 3D” to explore the intermediate model layers and their outputs.
🐞 Known Issues

The canvas may not respond on the first draw attempt. If that happens, try drawing again — it works fine afterward.
