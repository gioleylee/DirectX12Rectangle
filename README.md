# DirectX12Rectangle

A minimal Direct3D 12 project that renders a simple rectangle on screen. This project is designed as a beginner-friendly introduction to modern graphics programming using DirectX 12.

---

## 📌 Overview

**DirectX12Rectangle** demonstrates the basic setup of a Direct3D 12 rendering pipeline, including device initialization, command queues, swap chains, and rendering geometry using vertex buffers.

The goal of this project is to provide a clean and easy-to-understand starting point for learning DirectX 12 without unnecessary complexity.

---

## 🚀 Features

* Direct3D 12 initialization
* Window creation and swap chain setup
* Command queue and command list usage
* Basic vertex buffer for rendering geometry
* Renders a rectangle using GPU pipeline
* Double buffering

---

## 🛠 Requirements

* Windows 10 or Windows 11
* **Microsoft Visual Studio 2019 or 2022**
* Windows SDK (latest recommended)
* GPU with DirectX 12 support

---

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/DirectX12Rectangle.git
```

### 2. Open the project

* Open the `.sln` file in Visual Studio

### 3. Build

* Set configuration to `x64`
* Press `Ctrl + Shift + B`

### 4. Run

* Press `F5` to run with debugger
* Or `Ctrl + F5` to run without debugger

---

## 📁 Project Structure

```text
DirectX12Rectangle/
│
├── DirectX12Rectangle.sln
├── DirectX12Rectangle/
│   ├── DirectX12Rectangle.vcxproj
│   ├── src/
│   ├── include/
│   ├── shaders/
│   └── assets/
│
└── README.md
```

---

## 🧠 Learning Goals

This project helps you understand:

* How Direct3D 12 differs from older versions (like D3D11)
* Explicit GPU resource management
* Command-based rendering workflow
* Basic rendering pipeline setup

---

## ⚠️ Notes

* This project focuses on simplicity rather than optimization
* Error handling is minimal for clarity
* Intended for educational purposes

---

## 📚 Future Improvements

* Add color and textures
* Introduce index buffers
* Implement camera and transformations
* Add shader abstraction
* Expand to 3D rendering

---

## 📄 License

This project is open source and available under the MIT License.

---

## 🙌 Acknowledgements

* Microsoft DirectX 12 documentation
* Graphics programming tutorials and community resources
