# Chatbot hỏi đáp Y khoa (RAG + Ollama)

Chatbot trả lời bằng tiếng Việt dựa trên tài liệu của khoa và các dataset
y khoa (ViHealthQA, MedQuAD...), chạy trên Kaggle với Ollama.

<img width="452" height="797" alt="Screenshot 2026-11-10 150623" src="https://github.com/user-attachments/assets/ee0d744d-ea84-4420-97f6-d4bdc80b358d" />
<img width="450" height="796" alt="Screenshot 2026-11-10 150704" src="https://github.com/user-attachments/assets/fc4893d8-818d-4ce6-8f8f-4cc037e1f55d" />
<img width="452" height="791" alt="Screenshot 2026-11-10 150814" src="https://github.com/user-attachments/assets/05f493a8-00cc-4de2-a0fd-22063c46a139" />



## Cách chạy
1. Mở `notebooks/RAGchatbot.ipynb` trên Kaggle (GPU T4, Internet On).
2. Chạy lần lượt các cell từ trên xuống.

## Công nghệ
BAAI/bge-m3, FAISS, Ollama (qwen2.5:7b), Gradio
