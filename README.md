# 💫 About Me:
🎓 **Currently studying**: Data Science. I focus on bridging the gap between rigorous ML research and production-ready software engineering.

🔬 **Currently working on**: Reproducing and optimizing a **Time-Window Prediction Model for Traumatic Hemorrhagic Shock (THS)**. I implement **interpretable Machine Learning** (XGBoost & SHAP) using **stepped feature sets**—Vital Signs (VS), Routine Blood (RB), and Blood Gas (BG)—to predict shock onset up to 3 hours in advance.

🤖 **AI Engineering Focus**: Building modern AI pipelines. Actively developing projects using **Vision LLMs** for automated data extraction, building **RAG (Retrieval-Augmented Generation)** systems, and learning **LLM fine-tuning** alongside robust evaluation frameworks (LLM-as-a-judge).

⚙️ **System Architecture**: Applying scalable backend patterns (C#/.NET microservices, Saga, CQRS) to reliably deploy and orchestrate AI models and agents.

🤝 **Looking to collaborate on**: AI/ML projects, open-source medical tech, or high-performance backend systems.

## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jakub-arczewski-7b2978368/) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:jakubarczewski@gmail.com) 

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white) ![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white) ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) 
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-black?style=for-the-badge&logo=xgboost) 
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

# 🔬 Featured Research: THS Prediction Model
Replication of a clinical study using the **MIMIC-III** and **PLAGH-ERD** databases to proactively detect shock.
* **Performance**: Achieved an **AUROC of 0.935** for a 0.5h window using vital signs alone.
* **Enhanced Accuracy**: Performance increased to **AUROC 0.968** when integrating laboratory results (VS+RB+BG) for a 1h window.
* **Interpretability**: Applied **SHAP (SHapley Additive exPlanations)** to analyze clinical feature importance (Shock Index, Hemoglobin, Lactate).
* **Stepped Architecture**: Designed to adapt to different clinical scenarios—from pre-hospital settings (Vital Signs) to in-hospital intensive care (Lab Data).
