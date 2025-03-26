# 🖱️🎨 AI Virtual Mouse & AI Virtual Painter  

## 📌 Overview  
The **AI Virtual Mouse & AI Virtual Painter** is a **computer vision-based** application that allows users to **control the mouse and draw digitally** using **hand gestures**. Built with **OpenCV** and **MediaPipe**, this project eliminates the need for physical input devices by enabling hands-free interaction.  

## 🛠️ Features  
✔ **AI Virtual Mouse** – Control the cursor, click, scroll, and drag using hand gestures  
✔ **AI Virtual Painter** – Draw, erase, and change colors using intuitive hand movements  
✔ **Hand Tracking & Gesture Recognition** using **MediaPipe Hands**  
✔ **Smooth & Real-time Performance** with OpenCV  
✔ **No External Hardware Required** – Uses a standard webcam  

## 🚀 Tech Stack  
🔹 **Python** – Core language  
🔹 **OpenCV** – Image processing & hand tracking  
🔹 **MediaPipe** – Real-time hand gesture recognition  
🔹 **NumPy** – Data handling  
🔹 **PyAutoGUI** – Simulating mouse actions  

## 📂 Project Structure  
📁 AI_Virtual_Mouse_Painter
┣ 📜 mouse.py # AI Virtual Mouse script
┣ 📜 painter.py # AI Virtual Painter script
┣ 📜 utils.py # Helper functions
┣ 📜 requirements.txt # Dependencies list
┗ 📜 README.md # Project documentation

## 🎯 How It Works  
1️⃣ **Run the Virtual Mouse**: Move the cursor, perform clicks, scroll, and drag using hand gestures.  
2️⃣ **Run the Virtual Painter**: Use hand gestures to draw, erase, and switch colors dynamically.  
3️⃣ **Gesture Control**: Specific finger movements are mapped to mouse and drawing actions.  

## 📦 Installation & Setup  
```bash
# Clone the repository  
git clone https://github.com/NareshP215/AI-Virtual-Mouse-Painter.git  
cd AI-Virtual-Mouse-Painter  

# Install required dependencies  
pip install -r requirements.txt  

# Run the Virtual Mouse  
python mouse.py  

# Run the Virtual Painter  
python painter.py  
