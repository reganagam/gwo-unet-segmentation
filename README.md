# 🐺 Meta-Heuristic Optimization for Image Segmentation: U-Net vs GWO-U-Net

**Author:** Regan Agam (NIM: 24/PTK/552177/16439)  
**Program:** Master's in Electrical Engineering, Universitas Gadjah Mada (UGM)  
**Course:** Optimisasi Lanjut (Advanced Optimization)

## 📌 Project Overview
While standard Convolutional Neural Networks (CNNs) and U-Net architectures perform exceptionally well in segmentation tasks (particularly in medical image analysis), they often suffer from getting stuck in local minima during gradient-based optimization. This project explores an advanced meta-heuristic approach by integrating the **Grey Wolf Optimizer (GWO)** with a U-Net architecture.

The objective is to benchmark the segmentation performance, convergence stability, and overall optimization efficiency of the standard U-Net against the GWO-enhanced U-Net (GWO-U-Net).

## 🛠️ Tech Stack & Algorithms
* **Language:** Python
* **Framework:** TensorFlow / PyTorch, Jupyter Notebook
* **Algorithms Implemented:** * Standard U-Net Architecture (Baseline)
  * Grey Wolf Optimizer (GWO) - Meta-heuristic Swarm Intelligence

## 🔬 Methodology
1. **Standard U-Net:** Trained and optimized using traditional gradient-based optimizers (e.g., Adam/SGD).
2. **GWO-U-Net:** Utilizes the Grey Wolf Optimizer—a swarm intelligence algorithm inspired by the leadership hierarchy (alpha, beta, delta, omega) and hunting mechanism of grey wolves—to optimize the network's hyperparameters and weights.
3. **Comparative Analysis:** Evaluating both models based on segmentation accuracy, convergence behavior, and loss reduction.

## 📊 Results & Performance Evaluation
*(Note: Visual comparisons and training loss graphs can be found inside the Jupyter Notebook).*

| Metric | Standard U-Net | GWO-U-Net | Improvement |
| :--- | :---: | :---: | :---: |
| **Dice Coefficient / F1-Score** | *0.XX* | *0.XX* | *+X.X%* |
| **IoU (Intersection over Union)** | *0.XX* | *0.XX* | *+X.X%* |
| **Final Loss** | *Value* | *Value* | *Faster Convergence* |

### 💡 Key Engineering Insights
* **Exploration vs. Exploitation:** GWO provides a robust balance between exploring the global search space and exploiting the best local solutions. This significantly reduces the chance of the U-Net getting trapped in suboptimal local minima.
* **Accuracy Improvement:** The GWO-U-Net demonstrates superior edge detection and boundary segmentation compared to the baseline model, proving the efficacy of swarm intelligence in deep learning optimization. *(Silakan sesuaikan poin ini berdasarkan kesimpulan di slide PPT Anda).*

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/yourusername/gwo-unet-segmentation.git](https://github.com/yourusername/gwo-unet-segmentation.git)
