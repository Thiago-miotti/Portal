# 🌀 3D Portal Scene with Three.js

This project is a stylized 3D scene created using [Three.js](https://threejs.org/), showcasing a mystical portal with glowing lights, animated particles (fireflies), and custom shaders for a magical atmosphere.

<video src="static/VideoPortalGit.mp4" controls width="100%" />

## ✨ Technologies Used

- **Three.js**: 3D rendering
- **GLTFLoader + DRACOLoader**: optimized loading for `.glb` models
- **ShaderMaterial**: custom GLSL shaders for the portal and fireflies
- **lil-gui**: GUI to tweak live parameters (colors, sizes)
- **OrbitControls**: smooth camera controls

## 🎮 Features

- Custom animated portal with configurable gradient colors
- Fireflies using a shader-based particle system
- Orbit controls for real-time camera movement
- Baked textures for optimized lighting and performance

## 🛠 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

> Requires Node.js v16+ and a dev environment supporting ESModules and GLSL shader imports.

---

🧙‍♂️ Built as part of my Three.js learning journey — inspired by the [Three.js Journey](https://threejs-journey.com/) course.
