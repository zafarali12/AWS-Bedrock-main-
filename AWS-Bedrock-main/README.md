# 🚀 AWS Bedrock Playground

This repository is a **hands-on playground** for experimenting with **Amazon Bedrock Foundation Models** including:

- 🧠 Claude (Anthropic)
- 🦙 LLaMA2 (Meta)
- 🎨 Stable Diffusion (Image Generation)

It provides simple Python scripts to interact with these models using the AWS Bedrock service.

---

## 📂 Project Structure

```
.
├── app.py                # Main entry point for running the project
├── claude.py             # Claude model integration
├── llama2.py             # LLaMA2 model integration
├── stablediffusion.py    # Stable Diffusion model integration
├── test.json             # Sample input/output data
├── requirements.txt      # Project dependencies
├── .gitignore
├── LICENSE
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/zafarali12/AWS-Bedrock-main-.git
cd AWS-Bedrock-main-
```

### 2. Create and activate a virtual environment (recommended)

```bash
python -m venv venv
# Activate on Linux/Mac
source venv/bin/activate
# Activate on Windows
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Run the main application

```bash
python app.py
```

### Run specific models

- **Claude**

  ```bash
  python claude.py
  ```

- **LLaMA2**

  ```bash
  python llama2.py
  ```

- **Stable Diffusion**
  ```bash
  python stablediffusion.py
  ```

---

## 🔑 Requirements

- Python **3.9+**
- An **AWS Account** with **Bedrock enabled**
- AWS CLI installed and configured locally with your credentials:
  ```bash
  aws configure
  ```

---

## 📸 Example (Stable Diffusion)

```bash
python stablediffusion.py
```

Generates an image from text prompts using AWS Bedrock’s Stable Diffusion model.

---

## 🛡 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

##  Author

Developed by **Muhammad Zafar Ali** 

