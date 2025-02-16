# Fake News Detection using DistilBERT

## 📌 Project Overview
This project aims to detect **fake news** using **DistilBERT**, a transformer-based NLP model. The model is trained on a dataset of real and fake news articles, enabling it to classify unseen news articles as either **true** or **fake**.



## 📂 Repository Structure
```
📦 fake-news-detection-distilbert
├── 📂 Dataset
│   ├──Fake.csv
│   ├──True.csv           
├── README.md
├── fakeNewsDetection_DistilBert.ipynb

```

# 📌 Using CUDA in Your Projects  

## **1️⃣ Install CUDA Dependencies**  
For Python projects, install `cupy` for GPU computations:  
```bash
pip install cupy-cuda12x
```

For PyTorch:  
```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
```

## **2️⃣ Check GPU Availability in Python**  
```python
import torch
print(torch.cuda.is_available())
print(torch.cuda.device_count())
print(torch.cuda.get_device_name(0))
```





## ⚙️ Installation Guide
💡 Note: It is highly recommended to use a CUDA-enabled GPU (such as NVIDIA GPUs) for faster training. If a GPU is not available, training can be done on a CPU, but it will be significantly slower

## 1️⃣ Fork the Repository
- **Click the **Fork** button (top-right corner).**
- **This creates a copy of the repository under your GitHub account.**

## 2️⃣ Clone Your Forked Repository
```sh
git clone https://github.com/your-username/fake-news-detection-distilbert.git
cd fake-news-detection-distilbert
```
> Replace `your-username` with your actual GitHub username.

## 3️⃣ Create a New Branch (For Your Changes)
```sh
git checkout -b feature-branch
```
> Replace `feature-branch` with a meaningful branch name.

## 4️⃣ Make Changes and Commit
Modify the code, then stage and commit:
```sh
git add .
git commit -m "Description of changes"
```

## 5️⃣ Push Changes to Your Forked Repository
```sh
git push origin feature-branch
```

## 6️⃣ Create a Pull Request (PR)
1. Go to **your forked repository**.
2. Click on **Compare & pull request**.
3. Ensure the **base repository** is the original repo and the **head repository** is your fork.
4. Add a meaningful title and description.
5. Click **Create pull request**.

## 🛠️ Tech Stack Used
- **Python** 🐍 - Primary programming language
- **Transformers (Hugging Face)** - DistilBERT model for NLP
- **PyTorch** - Deep learning framework
- **Pandas** - Data processing
- **Matplotlib** - Data visualization


## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request. Any improvements, bug fixes, or new features are appreciated.


## 📜 License
This project is licensed under the MIT License.



## 📧 Contact
For any questions, reach out via [msaakaash@hotmail.com](mailto:msaakaash@hotmail.com) or **GitHub Issues**.

Happy Coding! 🚀

