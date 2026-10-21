# Victor Saunier

Master's Student in Electronics & Computer Science @ **CPE Lyon**  
Seeking a 6 to 12-month **Software Engineering Internship** starting in June 2027.

---

### 🛠 Tech Stack & Skills

- **Programming Languages:** C++ (C++20), Python, C, GLSL, VHDL, JavaScript
- **Frameworks & Libraries:** PyTorch, OpenCV, ONNX Runtime, OpenGL 3.3 Core, Dear ImGui
- **Developer Tools & Environments:** CMake, Google Test (GTest), Git, Linux/Unix
- **Core Competencies:** Systems Programming, Computer Vision & Anomaly Detection, Real-Time Rendering, Numerical Simulation

---

### 📌 Featured Projects

#### [Real-Time 3D Rendering Engine](https://github.com/victor-saunier/cpp-3d-renderer)
* **Built** a cross-platform renderer running at **1,500+ FPS** over **69K triangles** with automated **CMake (FetchContent)** and **Google Test** suites.
* **Reduced** VRAM vertex overhead by **82%** (208K to 35.9K vertices) by implementing an unordered_map deduplication pipeline for indexed **EBO** buffers.
* **Designed** custom GLSL shaders executing Blinn-Phong lighting integrated with an embedded **Dear ImGui** debug panel, enforcing strict RAII semantics (`= delete` copy) to eliminate GPU resource leaks.

#### [Edge-Vision Defect Inspection Pipeline](https://github.com/victor-saunier/defect-vision-screw)
* **Built** an unsupervised defect inspection pipeline achieving **90.8% AUROC** and **96.0% precision** on the industrial **MVTec AD** benchmark.
* **Implemented** multi-scale feature extraction (ResNet-18) with **k-NN spatial patch retrieval** and **OpenCV** morphological defect measurement ($mm^2$).
* **Accelerated** CPU inference throughput by **63%** (from 12.3 ms to **4.56 ms / 219 FPS**) via computational graph export to **ONNX Runtime**.

#### [3D Interactive Simulation & Physics Engine](https://github.com/victor-saunier/projet-3eti-tsi)
* **Engineered** real-time ball aerodynamics at a locked **60 FPS** using explicit **Euler numerical integration** (gravity, drag, semi-elastic bounces).
* **Programmed** real-time projectile physics handling parabolic trajectories, gravity, and sphere-plane/bounding-box collisions with momentum damping for 20+ entities.
* **Implemented** a programmable rendering pipeline featuring custom GLSL shaders (Phong illumination model) and 2D texture mapping.

---

### 📫 Connect

- **Email:** [victor.saunier@cpe.fr](mailto:victor.saunier@cpe.fr)
- **LinkedIn:** [Victor Saunier](https://www.linkedin.com/in/victor-saunier-6648b03a9)
- **Location:** Lyon, France
