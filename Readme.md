# 📚 Exam AI – Chat with Your Notes

---

## ✨ The Problem
Studying isn’t just about learning — it’s about searching.  
Scattered notes across PDFs, Docs, and Notion make it difficult to revise.  
Students waste time figuring out: *“Is this a 5-mark or a 10-mark question?”*  
and often write either too little or too much in exams.  

---

## 💡 The Solution
Instead of drowning in notes, just **chat with them!**  
You can ask questions like:  
👉 *“Explain virtualization in 5 marks.”*  
and get exam-ready answers instantly.  

---

## ⚙️ How It Works
1. **User Query** → You ask: *“Define IaaS in 10 marks.”*  
2. **Retrieve Chunks** → Notes are split, embedded, and stored in **Pinecone DB**.  
3. **Feed AI** → Relevant chunks + query → Prompt → LLM (**OpenAI**).  
4. **Answer** → Crisp, structured, exam-ready reply.  

---

## 🔥 Example
**Question (5 marks):** Explain virtualization.  

**Answer:**  
Virtualization is creating virtual versions of computing resources like servers, storage, and networks for efficient utilization and scalability.  

---

## 🚀 Why It Matters
- Save hours of revision  
- No guessing how much to write  
- Notes become instantly usable  
- Not just for students — professionals can use it to query large docs too  

---

## 🛠️ Tech Stack
- **n8n** → Workflow automation  
- **Google Drive** → Upload docs  
- **Pinecone Vector DB** → Memory + search  
- **OpenAI** → Embeddings + answers  

---

## ⚡ Setup Instructions
1. Clone the repository:  
   ```bash
   git clone https://github.com/vamshi137/RAG-Pipeline-Chatbot-using-n8n.git
Install dependencies (Python, Node.js, n8n).

Set up Pinecone and OpenAI API keys in environment variables.

Run n8n and import the workflow JSON file.

Upload your notes into Google Drive and connect via n8n.

Start chatting with your syllabus!

👨‍💻 Built By
Vamshi Yamjala
Ganesh Bijapurkar
Abu
