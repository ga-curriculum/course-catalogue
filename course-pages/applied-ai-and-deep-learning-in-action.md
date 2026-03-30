# Start Here: Applied AI & Deep Learning in Action

- **Format:** Instructor-Led
- **Duration:** 4 Days • 32 HoursTBD <!-- For delivery, fill in the instructors name. -->

---

## Overview

Step into the world of deep learning and applied AI with a hands-on, career-aligned course designed to take you from the fundamentals to real-world application. You’ll start by strengthening your foundation in Python, Git, and machine learning, then dive into neural networks, natural language processing, and AI engineering. 

Through practical labs and a capstone project, you’ll implement models in PyTorch, experiment with transformers in Hugging Face, and design ethical AI workflows using LangChain. By the end of the course, you’ll have a portfolio-ready project and the confidence to apply modern AI techniques responsibly and effectively in your work.

---

## Outcomes

1. **Demonstrate core machine learning skills** — Build, train, and evaluate supervised learning models using Python and scikit-learn.  
2. **Implement deep learning architectures** — Use PyTorch to construct, train, and optimize neural networks, including CNNs and RNNs.  
3. **Apply natural language processing and LLMs** — Represent text data through embeddings, build transformer-based models, and analyze results using Hugging Face pipelines.  
4. **Evaluate and improve model performance** — Benchmark models using performance metrics, costs, and bias analysis to select the right approach for business use cases.  
5. **Engineer responsible AI systems** — Apply fairness, transparency, and security principles in model deployment.  
6. **Leverage LangChain and vector databases** — Build prompt-based chains, create retrieval-augmented generation (RAG) systems, and experiment with context-aware AI applications.  
7. **Deliver an end-to-end AI solution** — Design, build, and present a complete AI project that integrates technical implementation with ethical and practical considerations.

---

## Prerequisites

There are no formal prerequisites; however, this course is best suited for learners who:
- Have prior experience using **Python** and basic programming concepts.
- Are familiar with **data analysis** or **machine learning basics** (helpful but not required).
- Are comfortable writing simple scripts and ready to deepen technical and applied AI skills.

Ideal for:
- Early-career data practitioners
- Engineers or developers expanding into AI/ML
- Professionals seeking hands-on, job-relevant AI skills

---

## System Requirements

### ✅ Required Installations

- ✅ **Python 3.9+** installed and working  
- ✅ **Jupyter Notebook** installed (`pip install notebook`)  
- ✅ **Git** installed and GitHub account created  
- ✅ **PyTorch** installed (`pip install torch torchvision torchaudio`)  
- ✅ **Scikit-learn** installed (`pip install scikit-learn`)  
- ✅ **Hugging Face Transformers** installed (`pip install transformers`)  
- ✅ **OpenAI API** installed (`pip install openai`) and API key configured  
- ✅ **LangChain** installed (`pip install langchain`)  
- ✅ **FAISS or Chroma Vector Database** installed (`pip install faiss-cpu` or `pip install chromadb`)  
- ✅ **Zoom Desktop Client** installed  
- ✅ **Slack** installed  
- ✅ **Google Chrome** browser ready  
- ✅ **Canvas access confirmed** (login credentials provided after enrollment)

### Sanity Check (Run Before Class Starts)

```bash
# Check Python and pip
python --version
pip --version

# Verify Jupyter installation
jupyter --version

# Test PyTorch
python -c "import torch; print('PyTorch OK:', torch.__version__)"

# Test Hugging Face Transformers
python -c "import transformers; print('Transformers OK:', transformers.__version__)"

# Test OpenAI API
python -c "import openai; print('OpenAI API OK')"

# Test LangChain
python -c "import langchain; print('LangChain OK')"
```



---

## Module Repos

| Module name | Associated Lab | Tool(s) Used |
| :--- | :--- | :--- |
| **[Foundations in Python and Git for AI](https://github.com/ga-curriculum/Foundations-in-Python-and-Git-for-AI)** | - Introduction to the course experience, expectations, and resources. <br> - Ice breakers <br> - Tech setup if needed | **Python, Pandas, Numpy, Jupyter Notebook / Google Colab** |
| **[Core Concepts of Machine Learning](https://github.com/ga-curriculum/Core-Concepts-of-Machine-Learning)** | [Baseline Builder: Logistic Regression](https://github.com/ga-curriculum/Lab-1-Logistic-Regression) <br> Train a logistic regression model on an image dataset (e.g., MNIST digits) | **Jupyter Notebooks, NumPy arrays and pandas DataFrames** |
| **[Neural Networks: Concepts and Evolution](https://github.com/ga-curriculum/Neural-Networks-Concepts-and-Evolution)** | [From Linear to Neural](https://github.com/ga-curriculum/Lab-2-1-From-Linear-to-Neural) <br> Replace logistic regression with a simple feedforward neural network using PyTorch. | |
| **[Deep Learning Toolkits in Practice](https://github.com/ga-curriculum/Deep-Learning-Toolkits-in-Practice)** | [Pre-Trained Power-Up](https://github.com/ga-curriculum/Lab-2-2-Pre-trained-Power-up) <br> Use a Hugging Face or torchvision pre-trained model on the same dataset. | **PyTorch, Hugging Face, torchvision** |
| **[Building Neural Nets](https://github.com/ga-curriculum/Building-Neural-Nets)** | [Deeper with PyTorch](https://github.com/ga-curriculum/Lab-2-3-Deeper-with-PyTorch) <br> Implement and train a more robust PyTorch model (add multiple layers, experiment with activation functions, and basic optimization). | **PyTorch** |
| **[Neural Net Architectures](https://github.com/ga-curriculum/Neural-Net-Architectures)** | [CNNs in Action](https://github.com/ga-curriculum/Lab-2-4-CNNs-in-Action) <br> Apply a CNN to the dataset and compare results with previous models. Optionally, explore transfer learning by fine-tuning a pre-trained CNN. | **PyTorch** |
| **[Model Training, Optimization, and Regularization](https://github.com/ga-curriculum/Model-Training-Optimization-and-Regularization)** | **Review Session** | **PyTorch** |
| **[Foundations of Modern NLP](https://github.com/ga-curriculum/Foundations-of-Modern-NLP)** | [Bag-of-Words to BERT](https://github.com/ga-curriculum/Lab-3-1-From-BOWs-to-BERT) <br> Represent reviews using CountVectorizer, TF-IDF, and embeddings (Word2Vec, BERT). Run a quick sentiment classification and compare results. | |
| **[NLP Pipelines](https://github.com/ga-curriculum/NLP-Pipelines)** | [Plug-and-Play Pipelines](https://github.com/ga-curriculum/Lab-3-2-Plug-and-Play-Pipelines) <br> Use Hugging Face’s pipeline API to run sentiment analysis on reviews. Test different pre-trained models (e.g., DistilBERT vs. RoBERTa). | **Hugging Face** |
| **[Introduction to Transformers](https://github.com/ga-curriculum/Introduction-to-Transformers)** | [Summarizer in Action](https://github.com/ga-curriculum/Lab-3-3-Summarizer-in-Action) <br> Apply a transformer model to summarize a batch of long reviews or translate them into another language. | |
| **[Evaluating NLP Models](https://github.com/ga-curriculum/Evaluating-NLP-Models)** | [Model Match-Up](https://github.com/ga-curriculum/Lab-3-4-Model-Match-up) <br> Compare two transformer models (e.g., BERT vs. DistilBERT) on the same dataset using benchmarks (accuracy, F1, inference speed, cost). Include a short reflection on bias and fairness. | |
| **[Responsible AI and Model Deployment](https://github.com/ga-curriculum/Responsible-AI-and-Model-Deployment)** | **Review Session** | |
| **[Fundamentals of Prompting and Chaining](https://github.com/ga-curriculum/Fundamentals-of-Prompting-and-Chaining)** | [Build Your First Chain](https://github.com/ga-curriculum/Lab-4-1-Build-your-First-Chain) <br> Use LangChain to call a chat model, create a custom PromptTemplate, and link prompts together into a simple chain. | **LangChain** |
| **[Vector Databases and QA](https://github.com/ga-curriculum/Vector-Databases-and-QA)** | [Ask the Knowledge Base](https://github.com/ga-curriculum/Lab-4-2-Ask-the-Knowledge-Base) <br> Load documents into a vector database, run similarity searches, and connect them to a LangChain Q&A pipeline for context-aware answers. | **LangChain** |
| **[Review Session + Capstone Workshop](https://github.com/ga-curriculum/Capstone-Project-Guideline-Template)** | [Applied AI Capstone: End-to-End Solution Workshop](https://github.com/ga-curriculum/capstone-workshop) <br> Learners will work on their capstone project. | |
| **[Final Project Presentation](https://github.com/ga-curriculum/applied-ai-and-deep-learning-in-action-capstone)** | Applied AI Capstone: End-to-End Solution <br> In this capstone, learners will plan, build, evaluate, and present a complete AI solution to a real-world problem of their choice. <br><br> **Final Project Due** | |


