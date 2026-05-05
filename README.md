# SVM Decision Boundary Visualization (2D Synthetic Datasets)

This project visualizes the decision boundaries of Support Vector Machine (SVM) classifiers using different kernels (linear, polynomial, RBF, sigmoid) on multiple 2D synthetic datasets. Implemented in Google Colab using `scikit-learn` and `matplotlib`.

## 📊 Dataset Used
- Blobs
- Circles
- Moons
- Linearly Separable Data
Created in Code itself

## ⚙️ Methodology
1. Generate 2D synthetic datasets using `make_blobs`, `make_circles`, `make_moons`.
2. Train SVM classifiers with various kernels.
3. Plot the decision boundaries for each dataset–kernel combination.
4. Compare performance visually and interpret model behavior.

## 💻 Implementation
- Developed and tested on Google Colab
- Libraries: `numpy`, `matplotlib`, `sklearn`

## 🧠 Results
Decision boundaries and classification regions are visualized for each kernel type. The plots demonstrate how kernel choice affects the classifier’s flexibility and performance on non-linear data.

## 📁 Files
- `SVM_visualization.ipynb` – Main Colab notebook
- `images/` – Contains generated decision boundary plots

---

## 📜 License
MIT License
