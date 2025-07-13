## 📁 Image Segmentation with Deep Learning in PyTorch

### 🧠 Overview

This project implements **U-Net**-based image segmentation using **PyTorch**. The model learns pixel-wise classification that separates objects from background in images. Key steps include data preprocessing, augmentation, custom dataset loading, model training, and performance visualization.

### 🚀 Features

- **U-Net Architecture**: Built from scratch with encoder–decoder structure and skip connections.
- **Custom Dataset Loader**: Leverages `torch.utils.data.Dataset` and `DataLoader` for efficient batching.
- **Data Augmentation**: Real-time transforms (`torchvision.transforms`) to improve generalization.
- **Training Pipeline**: Implements training loop with configurable hyperparameters, checkpointing, and GPU support.
- **Evaluation & Visualization**: Metrics tracking (e.g., IoU, Dice coefficient) and side-by-side mask comparison plots.

### 🧰 Tech Stack

- **Language**: Python 3.8+
- **Deep Learning**: PyTorch
- **Utilities**: NumPy, PIL, Matplotlib
- **Data Handling**: torchvision

### ⚙️ Installation & Usage

1. **Clone the repo**:
   ```bash
   git clone https://github.com/yourusername/image-segmentation-pytorch.git
   cd image-segmentation-pytorch
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Prepare your dataset**:
   - Place images and masks in `data/images/` and `data/masks/` respectively.
4. **Run training**:
   ```bash
   python train.py --epochs 50 --batch-size 16 --lr 1e-4
   ```
5. **Visualize results**:
   ```bash
   python visualize.py --checkpoint runs/exp1/checkpoint.pth
   ```
### 📫 Contact

Your Name - [liamharding@rocketmail.com](mailto\:liamharding@rocketmail.com)
