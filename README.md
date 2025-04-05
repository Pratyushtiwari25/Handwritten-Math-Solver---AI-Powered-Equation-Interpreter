

#  Handwritten Math Solver  
**AI-Powered Equation Interpreter | March 2024 – May 2024**

##  Overview

This project is an AI-powered application designed to **interpret and solve handwritten mathematical equations** using computer vision and symbolic computation. It provides an intuitive web interface where users can upload images of handwritten math expressions and receive real-time symbolic interpretation and solutions.

Built using **OpenCV**, **PyTesseract**, **SymPy**, and **Streamlit**, this tool is ideal for students, educators, and researchers looking to bridge the gap between handwritten inputs and digital computation.

---

## 📂 Dataset

### CROHME (Competition on Recognition of Online Handwritten Mathematical Expressions)
- **Description:** CROHME is a standard benchmark dataset used for handwritten mathematical expression recognition.
- **Usage:** The dataset was used for:
  - Training and testing OCR accuracy on real handwritten expressions.
  - Evaluating performance in recognizing a variety of math notations.
- **Access:** [CROHME Dataset Info](https://www.isical.ac.in/~crohme/)

---

## 🛠️ Technologies Used

| Tool/Library | Purpose |
|--------------|---------|
| **OpenCV** | Image preprocessing (grayscale, blurring, binarization) |
| **PyTesseract** | OCR for extracting handwritten text |
| **SymPy** | Parsing and solving mathematical expressions |
| **Streamlit** | Building the web-based user interface |
| **PIL** | Image handling and display |
| **NumPy** | Array operations and image manipulation |

---

## ✨ Features

- Upload handwritten math images (JPG/PNG).
- OCR-powered extraction of expressions using PyTesseract.
- Real-time symbolic parsing and solving using SymPy.
- Preprocessing using OpenCV for improved OCR accuracy.
- Clean and interactive Streamlit UI.
- Support for basic algebraic and arithmetic equations.

---

## 🚀 Getting Started

### 🔧 Installation

```bash
git clone https://github.com/your-username/handwritten-math-solver.git
cd handwritten-math-solver
pip install -r requirements.txt
```

### ▶️ Run the App

```bash
streamlit run app.py
```

---

## 📸 Preprocessing Steps (OpenCV)

- **Grayscale Conversion**: Enhances contrast for OCR.
- **Gaussian Blur**: Reduces noise in handwritten strokes.
- **Thresholding (Binarization)**: Converts image to binary for OCR compatibility.

---

## 🧠 OCR + Parsing Pipeline

1. **Image Upload** via Streamlit UI.
2. **OpenCV Preprocessing** to clean image input.
3. **PyTesseract OCR** extracts math expression as string.
4. **SymPy** parses the expression and computes the result.
5. Output: Displayed in a side-by-side layout — *Input Image*, *Recognized Expression*, and *Solution*.

---

## 📈 Example

- Input: Handwritten image of `2x + 3 = 7`
- Output:  
  - Recognized: `2*x + 3 = 7`  
  - Solution: `x = 2`

---

---

## 🙌 Acknowledgements

- [CROHME Dataset](https://www.isical.ac.in/~crohme/)
- [PyTesseract](https://github.com/madmaze/pytesseract)
- [Streamlit](https://streamlit.io/)
- [SymPy](https://www.sympy.org/)
