# Kernel-Density-Estimation
A comprehensive exploration of Kernel Density Estimation (KDE), covering kernel functions, bandwidth selection, boundary effects, probability leakage, and visualization. Includes code, mathematical insights, and presentation material.<br>

##  Overview

The project addresses:

- The motivation behind KDE and its advantages over histograms  
- Mathematical formulation of KDE  
- Comparison of various **kernel functions** (Gaussian, Epanechnikov, etc.)  
- Role of the **smoothing parameter (bandwidth)**  
- **Error metrics**: MSE and MISE  
- Key challenges like **boundary effects**, **probability leakage**, and **use of negative/asymmetric kernels**  
- Visual analysis using real and simulated datasets  

##  Contents

- `datasets/` – Three datasets used for KDE analysis  
- `final_estimation_notebook.ipynb` – Main Jupyter notebook implementing simulations and visualizations  
- `Kernel Density Estimation.pdf` – Presentation slides summarizing key concepts, methodology, results, and observations  
- `README.md` – Project overview  

##  Highlights

- Visual comparisons of KDE using different kernels and bandwidths  
- Experiments on bimodal, long-tailed, and bounded distributions  
- Implementation of **boundary correction** via reflection methods  
- Exploration of negative and asymmetric kernels and their effects on density estimation

##  References

- Silverman, B. W. (1986). *Density Estimation for Statistics and Data Analysis*  
- Jones, M. C. (1993). *Simple boundary correction for kernel density estimation*, Statistics and Computing  
- Akinshin, A. (n.d.). *Kernel density estimation boundary correction: reflection* — [aakinshin.net](https://aakinshin.net/posts/kde-bc-reflection/)

##  License

This project is licensed under the [MIT License](LICENSE).

