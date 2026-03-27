# Deep Dive into Support Vector Machines (SVM) – Kernel Trick

🚀 An in-depth guide to understanding the **Kernel Trick** in SVMs and its real-world applications.

---

## 📌 Project Overview

Support Vector Machines (SVM) are powerful supervised learning algorithms for classification and regression tasks.  
The **Kernel Trick** allows SVMs to handle **non-linearly separable data** efficiently by implicitly mapping input features into higher-dimensional spaces.

This project demonstrates:

- How the Kernel Trick works  
- Different types of kernels: Linear, Polynomial, RBF, Sigmoid  
- Mathematical intuition and kernel equations  
- Real-world dataset comparison using Breast Cancer Wisconsin (Diagnostic)  
- Visualizations of kernel transformations

---

## 🧠 Mathematical Formulation

**Linear Kernel:**  

K(x, y) = x · y

**Polynomial Kernel:**  

K(x, y) = (x · y + c)^d

**RBF Kernel:**  

K(x, y) = exp(-γ ||x - y||^2)

**Sigmoid Kernel:**  

K(x, y) = tanh(α x · y + c)

---

## 📊 Results & Comparison

| Kernel Type | Accuracy |
|-------------|---------|
| Linear      | 85%     |
| Polynomial  | 91%     |
| RBF         | 96%     |
| Sigmoid     | 75%     |

---

## 📷 Visualization

The project includes visualizations showing **how different kernels transform the dataset**.  
*(Add images/screenshots in the `assets` folder if available)*

---

## 📁 Repository Structure



---



## 🛠️ Technologies Used

- **Python** – Scikit-Learn, NumPy, Matplotlib  
- **Jupyter Notebook** – Data analysis & visualization  
- **React.js** – Frontend  
- **Vite** – Development server & bundler  

---

## 🎓 References

- [Scikit-Learn Documentation](https://scikit-learn.org/)  
- Vladimir Vapnik, *Statistical Learning Theory* (1998)  
- Andrew Ng’s Machine Learning Course (Stanford)

---

## 📬 Contact

- **GitHub:** [maratheonkar2002-web](https://github.com/maratheonkar2002-web)  
- **Email:** maratheonkar2002@gmail.com  

---

© 2026 Onkar Marathe | Deep Dive into Support Vector Machines – Kernel Trick

