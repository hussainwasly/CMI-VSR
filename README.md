# Beyond Scale: Toward Verifiable Autonomous Intelligence

This repository accompanies the manuscript:

**"Beyond Scale: Toward Verifiable Autonomous Intelligence"**

It provides implementation, experiments, and reproducible artifacts for the proposed **Cognitive Modular Intelligence (CMI)** framework.

---

## ⭐ Main Entry Point (Recommended)

### 👉 `CMI_IEEE_v20_with_CartSafe_v2_Cell9D.ipynb`

This is the **primary notebook** for the paper.

It contains the **main experimental results using CartSafe-v2**, including:

* Final evaluation of the CMI architecture
* HCRO (training) + CVS (inference) integration
* Enhanced environment with:

  * partial observability
  * stochastic dynamics
  * multiple safety constraints
* Full comparison against baselines

📌 **If you run only one file, run this notebook.**

---

## 📦 Repository Contents

### 🔬 Core Notebooks

* **`CMI_IEEE_v20_with_CartSafe_v2_Cell9D.ipynb` (MAIN)**
  Final experimental pipeline and results (CartSafe-v2).
  → Used for the **main claims in the paper**

* **`CMI_Cell9C_Standalone.ipynb`**
  Earlier standalone version (CartSafe-v1).
  Useful for:

  * controlled comparisons
  * ablation validation
  * reproducing intermediate results

---

### 📊 Results Packages

* **`cell9c_results.zip`**
  Results for CartSafe-v1 experiments:

  * per-seed logs
  * evaluation metrics
  * statistical outputs

* **`ieee_results_v19_package.zip`**
  Archived results from manuscript version v19:

  * included for reproducibility
  * enables cross-version validation

---

## 🧠 Key Concepts

* **CMI (Cognitive Modular Intelligence)**
  Hybrid system combining:

  * neural policy
  * learned world model
  * formal verification

* **HCRO (Hybrid Constrained Reinforcement Optimization)**
  Training objective integrating constraint satisfaction signals.

* **CVS (Candidate Verification and Selection)**
  Inference-time filtering using:

  * prospective simulation
  * constraint checking

* **CartSafe-v2 (Main Experimental Environment)**
  Extended environment designed to stress-test:

  * safety under uncertainty
  * interaction between planning and verification

  Features:

  * partial observability
  * stochastic transitions
  * multiple simultaneous constraints

---

## 🚀 Getting Started

### Requirements

* Python 3.9+
* Jupyter Notebook / JupyterLab
* PyTorch
* NumPy, SciPy, Matplotlib
* (Optional) SMT solver (e.g., Z3)

---

### Run the Main Experiment

```bash
jupyter notebook
```

Then open:

👉 `CMI_IEEE_v20_with_CartSafe_v2_Cell9D.ipynb`

Run all cells to reproduce the **main results**.

---

## 📈 Reproducibility

* Multi-seed evaluation (≥20 seeds)
* Fixed experimental protocols
* Metrics:

  * Cost Satisfaction Rate (CSR)
  * constraint violation rate
  * task return

The provided `.zip` files include:

* raw logs
* aggregated statistics
* reproducible outputs

---

## ⚠️ Notes

* The focus is on **mechanistic validation**, not large-scale benchmarking.
* CartSafe-v2 is designed as a **controlled stress-test environment** to isolate:

  * the role of verification
  * the interaction between simulation and safety constraints

---

## 📜 Citation

```bibtex
@article{cmi2025,
  title={Beyond Scale: Toward Verifiable Autonomous Intelligence},
  author={...},
  year={2025}
}
```

---

## 🔓 License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.

### Summary

* ✅ Free to use, share, and adapt for **non-commercial purposes**
* ✅ Attribution required
* ❌ Commercial use is **not permitted**

### Full License

https://creativecommons.org/licenses/by-nc/4.0/

---

### ⚠️ Commercial Use

If you are interested in **commercial use**, please contact the authors for permission.

---

## 📬 Contact

* Open an issue for questions or bugs
* Contributions and feedback are welcome

---
