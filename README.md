# Custom-Virtualized-Geometry-Renderer
A custom Virtualized Geometry LOD Rendering Engine : cluster-based real-time mesh simplification and LOD streaming system inspired by UE5's Nanite. This engine dynamically switches between multiple Levels of Detail using a virtualized geometry hierarchy, supporting view-dependent streaming and cluster-based simplification.


## ✨ Features

- 🔄 **Dynamic LOD Transitions** with hysteresis to prevent flickering  
- 🧩 **Cluster-Based Mesh Partitioning** for efficient culling and updates  
- 🚀 **View-Dependent Streaming** with bounding volume-based LOD switching  
- 🎯 **Real-Time Simplification** based on camera distance  

---
## 🔧 Technical Highlights

- 🛠️ Developed entirely from the ground up
- 📦 Minimal external dependencies: only [GLFW](https://www.glfw.org/), [GLM](https://github.com/g-truc/glm), and [Dear ImGui](https://github.com/ocornut/imgui)
- 🌲 BVH (Bounding Volume Hierarchy) used for cluster-based spatial organization
- ✂️ QEM (Quadric Error Metrics) used for geometry simplification
- 🎯 Per-cluster frustum culling for efficient rendering
- 📥 Dynamically loads and unloads cluster geometry based on frustum intersection

---
## 🎮 Ideal For

- Researchers exploring real-time mesh simplification  
- Developers building custom rendering engines  
- Anyone inspired by **Nanite** looking to experiment with similar techniques in OpenGL
---
## 🎥 Demo
![dynamic LOD](../../../Downloads/dynamic_LOD.gif)

## 🚧 Project Status

- 🔄 Currently in **active development**
- 🧪 Preparing for a potential **public release version**
- 📦 **Release coming soon** – stay tuned!


