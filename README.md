# 🧩 Mesh Fixer

A Blender add-on designed to **optimize the modeling and export workflow between Blender and Unreal Engine**.  
It automates tedious and repetitive tasks such as applying modifiers, transforms, fixing normals, and organizing material IDs — saving time and reducing errors in production.

---

## 🚀 Getting Started

### 1️⃣ Download the Add-on

Download the `.zip` version of the add-on 


---

### 2️⃣ Install the Add-on

1. In Blender, go to `Edit → Preferences`

![1](https://github.com/user-attachments/assets/c244c1f2-f19a-4a50-9323-c67cf82df334)


3. Open the **Get Extensions** tab and click **Install from Disk**
4. Select the `.zip` file you downloaded
5. Enable the add-on by checking the box next to **Mesh Fixer**

---

## 🔧 Features

Open the right-hand toolbar in the 3D Viewport by pressing `N`. Navigate to the **Mesh Fixer** tab to access all functions:

---

### ✅ 1. Apply Modifiers (Single or Batch)

Automatically apply all modifiers on selected objects or the entire scene.

- `To Selected` — Apply all modifiers to selected objects  
- `To All` — Apply all modifiers to all objects in the scene  

Useful for converting procedural models into editable geometry quickly.

---

### ✅ 2. Apply Transforms (Single or Batch)

Fix issues caused by unapplied transformations, such as incorrect bevels, solidify thickness, or mirror scaling.

- Automatically applies **location, rotation, and scale**
- Resets origin point to geometry center

- `To Selected` — Apply transforms to selected objects  
- `To All` — Apply transforms to all objects  

Ideal for ensuring export compatibility with Substance painter and UE, avoiding flipped normals or hidden faces.

---

### ✅ 3. Check and Fix Face Orientation

Incorrect face normals can cause disappearing or broken geometry in Substance Painter or Unreal Engine.  
This tool allows you to:

- Toggle face orientation display  
- Recalculate normals outside (`Shift + N` equivalent)  
- Flip normals for flat planes if needed

- `👁️` — Toggle face orientation visibility
- `Flip` — Flip normals for selected objects
- `To All` — Recalculate normals for all objects  

---

### ✅ 4. Batch Assign and Rename Materials

Maintain clean material IDs when exporting to Substance Painter or UE, avoiding messy material settings.

- Automatically assigns a new material to each object using its name + suffix
- Existing materials will be suffixed with `_1`, `_2`, etc.

- `Suffix` — Customize material suffix (default: `shader`)
- `To All` — Assign material IDs to all objects  

Example: An object named `Chair` will receive a material named `Chair_shader_1`.

---

### ✅ 5. One-Click Full Workflow Execution

This button runs **all the above steps** in the proper order:

1. Apply modifiers  
2. Apply transforms  
3. Recalculate normals  
4. Assign materials  

Click `Run` once your models are finalized to prepare the entire scene for export — fast and clean.

---

## 📂 Compatibility

- Blender 2.80 and above
- Tested with Blender → UE4/UE5, Substance Painter, and FBX export pipelines

---

## 🙌 Feedback & Contributions

This tool was born out of real production frustrations. If you find it helpful, feel free to star the repo, report bugs, or suggest new features!  
If you're a Blender creator and face recurring workflow problems — let’s make tools to solve them.

> **All creation begins in play.**  
Created by ZHONG HUI

