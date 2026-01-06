## 📁 Project Setup and Folder Structure

This section explains how to clone the repository and create the required project folders.

---

### 🔹 Clone the Repository

```bash
git clone https://github.com/nitixsh/CNN-BILSTM_IDS-Project.git
cd CNN-BILSTM_IDS-Project
mkdir models data src notebooks
echo "Models" > models/README.md
echo "Data" > data/README.md
echo "Scripts" > src/README.md
echo "Notebooks" > notebooks/README.md
git add .
git commit -m "Created folder structure"
git push origin main
```

## 📂 Folder Structure Overview

```text
CNN-BILSTM_IDS-Project/
│
├── models/        → Trained deep learning models (.h5 files)
├── data/          → Sample datasets or external dataset links
├── src/           → Training and evaluation scripts
├── notebooks/     → Jupyter notebooks for experimentation
└── README.md
```

