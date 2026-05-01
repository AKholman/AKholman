## Welcome to Iskandar Kholmanov's Github profile.

Machine Learning Engineer / Applied Scientist with a PhD in Physics and 8+ years solving complex scientific problems, plus 6+ years leading data-driven business initiatives. I design, build, and deploy production-grade ML and GenAI systems—from data ingestion and modeling to cloud deployment and monitoring. Strong background in LLMs, classical ML, MLOps, and end-to-end system ownership.
Co-author of 40+ peer-reviewed publications and U.S. patent holder.


### 🔧 Skills & Technologies:

✦  Programming, MLOps & Cloud:   
Python, SQL, Git, Docker, CI/CD (GitHub Actions), AWS (EC2, S3, Lambda, API Gateway), serverless ML, model serving, MLflow, Airflow, Evidently, cloud-native deployment

✦  GenAI & LLM Systems:   
LLM fine-tuning (LoRA / PEFT / QLoRA), Retrieval-Augmented Generation (RAG), LangChain, Hugging Face, vector databases (FAISS, ChromaDB), semantic search, offline & API-free inference

✦  Machine Learning & Deep Learning:    
PyTorch, TensorFlow, scikit-learn, XGBoost, classical ML, deep learning, transformers, time-series modeling

✦  Statistics, Analytics & Research:   
EDA, A/B testing, time-series analysis, statistical modeling, data visualization, experimental design

✦  Leadership & Impact:   
Cross-functional leadership, data-driven decision making, product-oriented ML, operational optimization   
    
    


    
### 🚀 Featured Projects (Production ML & GenAI Systems)

#### 1️⃣ End-to-End RAG System (Decoupled HF Deployment)

Built a production-ready, scalable LangChain-based RAG system using a Wikidata SPARQL ML knowledge source, sentence-transformers (all-MiniLM-L6-v2) embeddings, ChromaDB for vector retrieval, and FLAN-T5-Large for offline generation. Deployed a Dockerized FastAPI backend and Gradio frontend on separate Hugging Face Spaces with automated CI/CD via GitHub Actions, enabling fully self-hosted inference with no external API dependencies.
Tech: LangChain, HF, FastAPI, Docker, CI/CD, VectorDB

#### 2️⃣ LLM Fine-Tuning & Inference (Mistral-7B + LoRA / QLoRA)

Designed and executed an end-to-end LLM fine-tuning pipeline using Mistral-7B with LoRA/PEFT on Google Colab (T4 GPU). Built instruction-tuning datasets (system/user/assistant format) from Amazon reviews, synthetic Q&A, and product metadata. Deployed a 4-bit quantized (QLoRA) inference service with FastAPI and real-time chat access via ngrok. Analyzed model behavior and identified dataset scale and instruction-alignment limits affecting LoRA performance.
Tech: PyTorch, Transformers, PEFT, FastAPI, Quantization

#### 3️⃣ Production Time-Series Forecasting Platform

Developed a production-grade time-series ML system for stock price forecasting using PyTorch LSTM, orchestrated with Dockerized Airflow, tracked via MLflow, and monitored with Evidently. Deployed as a Streamlit application on Render using Yahoo Finance data. Benchmarked against SARIMA, Random Forest, XGBoost, and LSTM-Keras, achieving 1.64% MAPE on unseen data, outperforming classical and ML baselines.
Tech: PyTorch, Airflow, MLflow, Evidently, Streamlit

#### 4️⃣ Real-Time Fraud Detection (Serverless ML on AWS)

Built a production-style credit card fraud detection system for extreme class imbalance (~0.17% fraud). Performed Spark/SQL preprocessing in Databricks, trained and validated XGBoost (CPU) models on AWS EC2 (free tier), and stored versioned artifacts in S3. Deployed a serverless, low-latency inference API using AWS Lambda (container image) and API Gateway, with a Streamlit UI for real-time predictions. Achieved ROC-AUC 0.997, precision 0.89, recall 0.97.
Tech: XGBoost, AWS Lambda, API Gateway, Databricks, Serverless ML


### 🏆 Research & Achievements:
- **PhD in Physics**. My research focused on **materials science** and data analysis, resulting in over **40+ peer-reviewed publications**.
- **Patent**: US Patent ##9477128 for **Graphene/Metal Nanowire Hybrid Transparent Conductive Films**.

### 📫 How to Reach Me:
- **LinkedIn**: [my_linkedin](https://www.linkedin.com/in/iskandar-kholman/)
- **Email**: [my_email](mailto:iskandar.kholmanov@gmail.com)
- **GitHub**: [my_github](https://github.com/AKholman)

---

**Let's Connect!**  
I’m always open to collaborating on interesting data-driven projects. Feel free to reach out if you want to chat about **data science**, **machine learning**, or **AI applications**!
