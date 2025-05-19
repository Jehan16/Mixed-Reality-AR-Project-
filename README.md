# Augmented Reality Web App – A-Frame + AR.js

This project demonstrates a web-based Augmented Reality (AR) experience using A-Frame and AR.js. It allows users to view and interact with 3D models rendered on top of physical markers through their mobile device cameras.

---

## 📦 Features

- 📱 Marker-based AR using webcam or mobile camera
- 🎨 Displays **4 unique 3D models** tied to **4 different custom markers**
- 🔊 Sound and animation support
- ⚡ Lightweight, works in the browser (no app required)

---

## 🚀 Getting Started

### 1. Clone / Download this project

git clone https://github.com/your-username/ar-multi-marker-app.git

shell
Copy
Edit

### 2. Install Local Web Server (with HTTPS support)

Install globally:
npm install -g local-web-server

perl
Copy
Edit

Or use alternative like:
npm install -g lite-server

pgsql
Copy
Edit

### 3. Start the server (with HTTPS)

For `local-web-server`:
ws --https

go
Copy
Edit

For `lite-server` (recommended for live reload):
lite-server

yaml
Copy
Edit

### 4. Open the URL on your mobile

Visit:
https://<your-local-ip>:8000

yaml
Copy
Edit

> ⚠️ Mobile and PC must be connected to the same Wi-Fi.

---

## 📁 File Structure

/
├── index.html # Main AR scene with 4 markers + models
├── model1.glb # GLB animated model 1
├── model2.glb # GLB animated model 2
├── model3.glb # GLB animated model 3
├── model4.glb # GLB animated model 4
├── marker1.patt # Custom marker pattern 1
├── marker2.patt # Custom marker pattern 2
├── marker3.patt # Custom marker pattern 3
├── marker4.patt # Custom marker pattern 4
├── sound.mp3 # Optional background sound
└── README.md

yaml
Copy
Edit

---

## 🖨️ Marker Setup

Generate `.patt` files using the [AR.js Marker Generator](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html). Print or display the marker images clearly for the camera to detect.

---

## 📚 Tech Stack

- [A-Frame](https://aframe.io)
- [AR.js](https://github.com/AR-js-org/AR.js)
- [GLTF / GLB Models](https://github.com/KhronosGroup/glTF)
- JavaScript / HTML

---

## 💡 Tips

- Use `.glb` format for animation support and better performance.
- Always run with HTTPS for full camera access on mobile.
- Prefer lightweight, low-poly models for smoother rendering.

---

## 📸 Demo

> Coming soon — include screenshots or a Loom video link here.

---

## 🧑‍💻 Author

Developed by IT21804342 / IT21814242 / IT21828966
