%%writefile README.md
# 🧮 Token Counter using Meta-Llama-3-8B-Instruct

This project is a **token counting chatbot** built using **Meta-Llama-3-8B-Instruct** on Hugging Face.

## 🚀 Features
- Token counting for both inputs and outputs  
- Local caching for faster reloads  
- Simple terminal and Gradio UI modes

## ▶️ Run in Google Colab
1. Open the Colab notebook.  
2. Run all cells to load the model and start chatting.  
3. Make sure you log in to Hugging Face if the model is gated:
   ```python
   from huggingface_hub import notebook_login
   notebook_login()
## 🖼️ Model Output
`` markdown 
![Model Output](assets/output.png)


