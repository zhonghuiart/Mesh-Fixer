# 🧩 Mesh Fixer

<img src="https://github.com/zhonghuiart/Batch-Cleanup/blob/6b31ae3ba339616bcd1b84b12fed2fa0d6ebdb50/images/superhive.png" width="800"/>

A Blender add-on designed to **optimize the modeling and export workflow between Blender and Unreal Engine**.  
It automates tedious and repetitive tasks such as applying modifiers, transforms, fixing normals, and organizing material IDs — saving time and reducing errors in production.

🔗 Download the addon on Gumroad: [Mesh Fixer](https://zhonghuiart.gumroad.com/l/fxjnf)

---

## 🚀 Getting Started

### 1️⃣ Download the Add-on

Download the `.zip` version of the add-on 

<img src="https://github.com/zhonghuiart/Mesh-Fixer/blob/4ec720d34d75c0393038f3ded106fd86ac95b732/images/download.png" width="600">

---

### 2️⃣ Install the Add-on

1. In Blender, go to `Edit → Preferences`

<img src="https://github.com/zhonghuiart/Mesh-Fixer/blob/e7c18bdaadc873740e9f46d5ca29e0d017976033/images/1.png?raw=true" width="400"/>


2. Open the **Get Extensions** tab and click **Install from Disk**

<img src="https://github.com/zhonghuiart/Mesh-Fixer/blob/e7c18bdaadc873740e9f46d5ca29e0d017976033/images/2.png?raw=true" width="600">

3. Select the `.zip` file you downloaded
4. Enable the add-on by checking the box next to **Mesh Fixer**

<img src="https://github.com/zhonghuiart/Mesh-Fixer/blob/ce035da90605bf88d00df27849ae6220dd6f55e2/images/3.png?raw=true" width="600">


---

## 🔧 Features

Open the right-hand toolbar in the 3D Viewport by pressing `N`. Navigate to the **Mesh Fixer** tab to access all functions:

<img src="https://github.com/zhonghuiart/Mesh-Fixer/blob/4ec720d34d75c0393038f3ded106fd86ac95b732/images/4.png?raw=true" width="600">

---

### ✅ 1. Apply Modifiers (Single or Batch)

<img src="https://github.com/zhonghuiart/Mesh-Fixer/blob/4e14e52507ca53258cb1b58dab61b7c342fbec85/images/modifiers.png?raw=true" width="800">

Automatically apply all modifiers on selected objects or the entire scene.

- `To Selected` — Apply all modifiers to selected objects  
- `To All` — Apply all modifiers to all objects in the scene  

Useful for converting procedural models into editable geometry quickly.

---

### ✅ 2. Apply Transforms (Single or Batch)

<img src="https://github.com/zhonghuiart/Mesh-Fixer/blob/4e14e52507ca53258cb1b58dab61b7c342fbec85/images/transform.png?raw=true" width="800">

Fix issues caused by unapplied transformations, such as incorrect bevels, solidify thickness, or mirror scaling.

- Automatically applies **location, rotation, and scale**
- Resets origin point to geometry center

- `To Selected` — Apply transforms to selected objects  
- `To All` — Apply transforms to all objects  

Ideal for ensuring export compatibility with Substance painter and UE, avoiding flipped normals or hidden faces.

---

### ✅ 3. Check and Fix Face Orientation

<img src="https://github.com/zhonghuiart/Mesh-Fixer/blob/4e14e52507ca53258cb1b58dab61b7c342fbec85/images/face.png?raw=true" width="800">

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

<img src="https://github.com/zhonghuiart/Mesh-Fixer/blob/4e14e52507ca53258cb1b58dab61b7c342fbec85/images/material.png?raw=true" width="800">

Maintain clean material IDs when exporting to Substance Painter or UE, avoiding messy material settings.

- Automatically assigns a new material to each object using its name + suffix
- Existing materials will be suffixed with `_1`, `_2`, etc.

- `Suffix` — Customize material suffix (default: `shader`)
- `To All` — Assign material IDs to all objects  

Example: An object named `Chair` will receive a material named `Chair_shader_1`.

---

### ✅ 5. One-Click Full Workflow Execution

<img src="https://github.com/zhonghuiart/Mesh-Fixer/blob/4e14e52507ca53258cb1b58dab61b7c342fbec85/images/runall.png?raw=true" width="600">

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

