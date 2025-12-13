# 🧁 CS-330 Final Project – 3D Baking Counter Scene (OpenGL)

## 📌 Project Overview
This repository contains my **CS-330 Final Project**, a three-dimensional scene built in **C++ and OpenGL** that recreates a simple baking setup on a kitchen countertop. The project focuses on low-polygon modeling, object placement, lighting, camera navigation, and clean, modular code design.

## 🧱 Scene Description
The 3D scene represents a baking workspace and includes the following objects:

- **Mixing Bowl** (multi-primitive object)
- **Rolling Pin**
- **Digital Scale**
- **Bowl Scraper**
- **Measuring Cup**
- **Countertop Plane** (environment)

All objects were modeled using simple primitives such as **spheres, cylinders, boxes, tapered cylinders, and planes**, with an emphasis on keeping geometry low-poly and easy to manage.



## 🎨 Textures & Lighting
- At least **two objects are textured** using royalty-free image textures.
- The scene includes **multiple light sources**, including:
  - A **point light**
  - A **colored light**
- Lighting is implemented using the **Phong shading model** (ambient, diffuse, and specular components) to provide depth and shading across all objects.


## 🎥 Camera Controls & Interaction

### Movement
- **W / A / S / D** – Move forward, left, backward, and right  
- **Q / E** – Move the camera down and up  

### Orientation
- **Mouse movement** – Adjusts camera pitch and yaw  
- **Mouse scroll wheel** – Adjusts camera movement speed  

### Projection Modes
- A keyboard toggle allows switching between:
  - **Perspective projection**
  - **Orthographic projection**


## 🧩 Code Organization
The project is written using a modular approach to improve readability and reuse. Key helper functions manage:

- Object transformations (scaling, rotation, translation)
- Shader materials and textures
- Camera movement and orientation
- Scene rendering

This structure allows new objects to be added easily and keeps the rendering logic organized.
