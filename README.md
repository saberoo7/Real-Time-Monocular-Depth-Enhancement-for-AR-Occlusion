🧠 Real-Time Monocular Depth Enhancement for AR Occlusion
Computer Vision Midterm Project — Team DepthVision25 (CV25)
Optimizing real-time monocular depth estimation for mobile AR headsets using MiDaS, temporal smoothing, and self-supervised fine-tuning.
🚀 Quick Start
Environment Setup
# Create and activate environment
conda create -n depthvision python=3.10 -y
conda activate depthvision

# Install dependencies
pip install torch torchvision opencv-python numpy pillow matplotlib onnxruntime
📦 Dataset Links
NYU Depth V2: https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html
KITTI Depth Dataset: https://www.cvlibs.net/datasets/kitti/
TUM-RGBD: https://vision.in.tum.de/data/datasets/rgbd-dataset
📁 Project Structure
DepthVision25/
├── train.py           # Fine-tuning and training script
├── evaluate.py        # Evaluation pipeline (RMSE, AbsRel, Flicker Index)
├── optimize_mobile.py # Model quantization & ONNX export
├── requirements.txt   # Dependencies
├── README.md          # This file
└── ROADMAP.md         # Weekly plan and progress log
💻 Script Stubs
Training Script
# train.py
def main():
    """Training pipeline for MiDaS-based depth enhancement"""
    print("Training pipeline - to be implemented")
    # TODO: Implement fine-tuning, temporal smoothing, and data loading

if __name__ == "__main__":
    main()
Evaluation Script
# evaluate.py
def main():
    """Evaluation pipeline for model performance"""
    print("Evaluation pipeline - to be implemented")
    # TODO: Implement RMSE, AbsRel, and temporal flicker evaluation

if __name__ == "__main__":
    main()
📊 Evaluation Metrics
RMSE (Root Mean Square Error)
AbsRel (Absolute Relative Error)
Temporal Flicker Index
Occlusion Quality (subjective AR evaluation)
⚙️ Implementation Details
Framework: PyTorch
Baseline: MiDaS small model
Enhancements: Temporal smoothing, self-supervised fine-tuning, and model quantization
Deployment: ONNX / TensorRT for mobile MR headsets
👥 Team
Otakhon Toshpulatov (Coordinator, GitHub: Otakhon-T)
