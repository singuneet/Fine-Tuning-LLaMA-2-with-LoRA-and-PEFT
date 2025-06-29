
# 🦙✨ Fine-Tuning LLaMA-2 with LoRA and PEFT

🚀 **Fine-tune Meta’s LLaMA-2 efficiently using LoRA, PEFT, and BitsAndBytes quantization in Colab.**

---

## 📂 #Overview

- 🔗 Loads **LLaMA-2** with 4-bit quantization (BitsAndBytes) to reduce GPU memory usage  
- 🛠️ Applies **LoRA (Low-Rank Adaptation)** for parameter-efficient tuning via **PEFT**  
- 🤗 Uses **TRL’s SFTTrainer** for supervised fine-tuning on your custom dataset

---

## 💻 #TechStack

- 🐍 Python  
- 🔥 PyTorch  
- 🤗 Transformers  
- 🛠️ PEFT  
- 📝 TRL  
- 🧮 BitsAndBytes

---

## ⚙️ #Usage

1. **Clone the repository**

    ```bash
    git clone https://github.com/yourusername/fine-tune-llama2.git
    cd fine-tune-llama2
    ```

2. **Open the notebook**

    - Open `Fine_tune_Llama_2.ipynb` in **Google Colab**.

3. **Run cells sequentially**

    - Install dependencies  
    - Load your dataset  
    - Start fine-tuning

4. **Save outputs**

    - Save fine-tuned weights locally or push to Hugging Face Hub.

---

## 📦 #Outputs

✅ Fine-tuned **LLaMA-2 model weights** ready for downstream NLP tasks.

---

## ⚠️ #Notes

- Requires **GPU runtime with CUDA 12.1 or lower** for BitsAndBytes compatibility.  
- Adjust dataset paths and hyperparameters to match your use-case.

---

## 📜 #License

This project is licensed under the [MIT License](LICENSE).

---

## ✨ #Connect

⭐ **If you find this useful, give a star!**  
🔗 **Connect with me on [LinkedIn]([https://linkedin.com/in/guneet-singh-bagga-86b42a221]) for collaborations.**


