## ImportPlyMesh (MayaMeshTools builds)

This repository provides a pre-compiled version of the **MayaMeshTools** plugin, specifically built for **Autodesk Maya 2026** on **Windows**. This tool allows you to import single mesh files and sequences of mesh files (OBJ, PLY, and MZD) as a single node in Maya.

### 📁 What's Included

* `MayaMeshTools.mll`: The compiled plugin binary.
* `scripts/`: Python/MEL scripts required to generate the "Mesh Tools" menu in Maya.

---

### 🛠 Installation & Activation

Follow these steps to install the tool on your workstation:

#### 1. Copy the Scripts

1. Download this repository and open the `scripts` folder.
2. Copy all files inside.
3. Navigate to your local Maya scripts directory:
`Documents\maya\2026\scripts`
4. Paste the files there.

#### 2. Save the Plugin File

1. Copy the `MayaMeshTools.mll` file to a stable location on your computer or C:\Program Files\Autodesk\Maya2026\bin\plug-ins.

#### 3. Load the Plugin in Maya

1. Launch **Maya 2026**.
2. Go to **Windows > Settings/Preferences > Plug-in Manager**.
3. Click the **Browse** button at the bottom.
4. Locate and select your `MayaMeshTools.mll` file.
5. In the Plug-in Manager list, find `MayaMeshTools.mll` and check:
* **Loaded**
* **Auto load** (so it stays active for your next session)



---

### 🚀 Usage

After activation, a new menu called **Mesh Tools** will appear in the top menu bar of Maya.

1. Click **Mesh Tools > Create MeshLoader**.
2. In the **Attribute Editor** for the new node:
* **Mesh File:** Browse to your `.ply` or `.obj` file.
* **Sequence:** If you are loading an animation, use `#` as a placeholder for frame numbers (e.g., `frame_###.ply`).
* **Active:** Toggle this to see the mesh in your viewport.



---

### ⚖️ License

Original code by InteractiveComputerGraphics (Jan Bender). Distributed under the **MIT License**. This specific build is provided for educational use only.
