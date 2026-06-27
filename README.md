# Hi, I'm Diego Paez 👋

---

## 🚀 Featured Projects & Engineering Research

### 📈 [1. Short-Term Ridership Forecasting for Mexico City's Cablebús System](https://github.com/DiegoEPaez/transit-ml)
*An end-to-end machine learning pipeline comparing statistical, tree-based, and deep learning architectures to predict ridership for Mexico City's Cablebús system.*
* **The Core Tech:** LightGBM, PyTorch (LSTM), Facebook Prophet, Statsmodels (SARIMA), Optuna.
* **Architectural Strategy:** Implemented isolated, line-specific models to capture unique demographic flows. Developed a **direct multi-model forecasting horizon approach** (separate models per lead day) to explicitly prevent the compounding error propagation typical of recursive time-series setups.
* **Impact:** Provides stable uncertainty quantification for long-term urban risk management and operational planning.

### 💰 [2. Financial Time-Series Optimization Framework](https://github.com/DiegoEPaez/fin-forecast)
*statistical analysis and deep learning applied to financial market indicators and forecasting.*
* **The Core Tech:** Python, Pytorch, Scikit-Learn, Pandas, Advanced Feature Engineering.
* **Architectural Strategy:** Built a robust validation pipeline specifically tailored for non-stationary financial data, incorporating strict walk-forward cross-validation to eliminate data leakage and optimize feature importance metrics under high-noise conditions.

### 👁️ [3. Unsupervised Optical Flow Inference Pipeline](https://github.com/DiegoEPaez/optical-flow)
*An engineering exploration into leveraging massive, unlabeled video datasets to train deep learning architectures for pixel-level motion estimation.*
* **The Core Tech:** PyTorch/OpenCV, FlowNet Simple, YouTube-8M Dataset, Motion Analysis Fundamentals.
* **Architectural Strategy:** Developed a custom modification over the **FlowNet Simple** backbone to accelerate convergence and optimize inference metrics. Built a pipeline targeting the complexities of training on raw web video, addressing challenges in frame-rate sampling dynamics (large vs. small displacements) and identifying data-cleansing strategies to isolate noise like scene cuts and text overlays.

### ☕ [4. Low-Level Deep Learning Engineering from Scratch](https://github.com/DiegoEPaez/dl-java)
*An educational and rigorous implementation of neural network fundamentals written purely in Java without external ML libraries.*
* **The Core Tech:** Java (Object-Oriented Architecture), Matrix Mathematics.
* **Architectural Strategy:** Built backpropagation, weight initialization schemes, activation functions, and gradient descent optimization completely from first principles. This repository highlights a deep, foundational understanding of memory allocation, matrix operations, and the core mathematical mechanics behind modern AI frameworks.

---

## 🛠️ Tech Stack & Tooling

* **Languages:** Python, Java, Bash, SQL, LaTeX.
* **Frameworks & AI:** PyTorch, LightGBM, Optuna, Scikit-Learn, Prophet, OpenCV.
* **MLOps & Infrastructure:** Poetry, Git, Docker, CI/CD Pipelines.
* **Specializations:** Time-Series Forecasting, Deep Generative Learning, Distributed Systems Concepts.

---

## 📬 Connect with Me

* **LinkedIn:** [linkedin.com/in/diegopaez](https://www.linkedin.com/in/diego-paez-9653737b/) * **GitHub:** [@DiegoEPaez](https://github.com/DiegoEPaez)
