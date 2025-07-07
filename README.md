# 🚀 Kaggle GPU Setup and Testing Guide

## 📋 Steps to Enable GPU:

### 1. ⚙️ **Go to Notebook Settings**
- Click the **"Settings"** button in the top right corner
- Or open the **"Settings"** panel on the right side of the page

### 2. 🔧 **Change Accelerator Setting**
- Find the **"Accelerator"** section
- Change from **"None"** to **"GPU T4 x2"** or **"GPU P100"**
- Make sure **"Internet"** is **"On"** (required for package installation)

### 3. 💾 **Save & Run All**
- Click the **"Save Version"** button
- Or use **Ctrl+S** keyboard shortcut
- The notebook will automatically restart with GPU enabled

### 4. ✅ **GPU Verification**
- Run the cells below to verify GPU is active

---

## ⚡ GPU Usage Limits:
- **Free Tier:** ~30 hours of GPU usage per week
- **Kaggle Competitions:** Can earn additional GPU hours
- **Performance:** T4 > P100 (T4 recommended for new projects)

---

## 🎯 What We'll Do in This Notebook:
1. Check GPU status
2. 🧠 Test PyTorch + CUDA
3. 📊 GPU performance benchmarking  
4. 🚀 Prepare for YOLOv11
