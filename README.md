# Blender-Scripts

This repository contains a collection of **Blender `.blend` files**. Each file may include embedded Python scripts (`bpy`) that generate or modify the 3D scene when run inside Blender.

## 🧩 How to Open and Use

1. Download or clone this repository.  
2. Open **Blender**.  
3. Go to **File → Open** and select any `.blend` file from the repository.  
4. To run any embedded scripts:  
   - Switch to the **Scripting** workspace (top menu).  
   - Open the **Text Editor** panel and look for scripts saved inside the `.blend` file.  
   - Click **Run Script** (▶️) to execute the script and update the scene.  
5. Press **F12** or go to **Render → Render Image** to render the scene.

## ⚙️ Requirements
- **Blender 4.3+**  
- No additional add-ons required.  
- All scripts use Blender’s built-in `bpy` module.

## 🖼️ Output
Each `.blend` file can generate or render its own 3D scene. Rendered images can be saved using Blender’s render settings.
