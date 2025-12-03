# 🌱 PlantDocBot — Dataset Setup & Preparation

This project prepares the **PlantVillage** and **PlantDoc** datasets for building a plant disease detection chatbot.

---

## 📁 Project Structure

The notebook automatically creates the following directory structure:

```
PlantDocBot/
└── data/
    ├── plantvillage/
    ├── plantdoc/
    ├── text_corpus/
    └── image_data.csv
```


---

## 📥 Dataset Download

The notebook clones two public datasets:

- **PlantVillage Dataset**  
  https://github.com/spMohanty/plantvillage-Dataset

- **PlantDoc Dataset**  
  https://github.com/pratikkayal/PlantDoc-Dataset

Both datasets are stored inside `data/plantvillage` and `data/plantdoc`.

---

## 🔍 Image Discovery & Verification

The script performs:

- Recursive search for image files (`.jpg`, `.png`, `.jpeg`, `.bmp`)
- Detection of folders containing plant images
- Display of a random sample image with correct RGB colors

---

## 🗂 CSV Mapping Creation

A `image_data.csv` file is generated containing:

- **image_path** → absolute image file path  
- **label** → category/folder name inferred from directory structure  

Useful for:

- Training machine learning models  
- Organizing datasets  
- Chatbot ingestion pipelines  

---

## ▶️ How to Use

Run the notebook steps in order:

1. Create project folders  
2. Clone datasets  
3. Search for image directories  
4. Preview a random image  
5. Generate the CSV mapping  

---

## 📌 Output Files

✔ Dataset folders created  
✔ Verified sample image displayed  
✔ `image_data.csv` containing image paths and labels  

---
