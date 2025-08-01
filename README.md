# CV Chatbot using Sentence Transformers + FAISS + Gradio
This project is an interactive chatbot that answers questions about a candidate's technical background using a cleaned version of their CV. It uses local embeddings generated by `sentence-transformers` and performs semantic search using `FAISS`. The chatbot interface is built using `Gradio`.
## 🚀 Project Description
This chatbot allows users to ask questions about a candidate's technical experience, skills, and projects. 
It retrieves the most relevant information from the CV and returns it as a response using semantic similarity.
The chatbot is designed to run entirely locally (no OpenAI API required), making it free and privacy-friendly.
---

## 🛠️ Technologies Used
- **Python 3**
- **Gradio** – for the chatbot interface
- **sentence-transformers** – for generating text embeddings
- **FAISS** – for fast similarity search
- **python-docx** – for reading the CV file

## 👩‍💻 Role and Contributions
- Extracted and cleaned technical content from a DOCX CV file
- Used `sentence-transformers` to generate vector embeddings of CV text
- Indexed the embeddings using `FAISS` for fast similarity search
- Built a chatbot interface using `Gradio` to allow natural language queries
- Deployed the chatbot in Google Colab for easy access and testing
## 📸 Screenshots
<img width="940" height="271" alt="image" src="https://github.com/user-attachments/assets/cc24b691-cfe5-4f0a-8cb0-e08942c9b23b" />
<img width="940" height="362" alt="image" src="https://github.com/user-attachments/assets/68e5ba19-f6f4-4c54-b317-7465540f6bfd" />

 
