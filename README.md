# DermAI - AI-Powered Skin Disease Chatbot

DermAI is an AI-powered medical chatbot that combines **deep learning-based skin disease classification** with **Retrieval-Augmented Generation (RAG)** to provide preliminary skin condition information and medical knowledge assistance.

## How to Run?

### 1. Clone the Repository

```bash
git clone https://github.com/nehasaik15/Skindisease_Chatbot.git
```

Navigate into the project directory:

```bash
cd Skindisease_Chatbot
```

---

### 2. Create a Conda Environment

```bash
conda create -n medibot python=3.10 -y
conda activate medibot
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Configure API Keys

Create a `.env` file in the root directory and add your Pinecone and Groq API credentials:

```env
PINECONE_API_KEY="your_pinecone_api_key"
GROQ_API_KEY="your_groq_api_key"
```

---

### 5. Store Embeddings in Pinecone

Run the following command to generate embeddings and store medical knowledge in the Pinecone vector database:

```bash
python store_index.py
```

---

### 6. Run the Application

Start the chatbot:

```bash
python app.py
```

Open your browser and visit:

```
http://localhost:5000
```

---

## Tech Stack Used

### Programming Language
- Python

### Artificial Intelligence & LLM Frameworks
- LangChain
- Groq LLM

### Machine Learning & Deep Learning
- PyTorch
- ResNet-18
- Computer Vision

### Vector Database
- Pinecone

### Web Framework
- Flask

### AI Techniques
- Supervised Learning
- Transfer Learning
- Retrieval-Augmented Generation (RAG)
