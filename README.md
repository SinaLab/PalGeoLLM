

# PalGeoLLM

**PalGeoLLM** is a project dedicated to Palestinian geography and history. It features a high-quality Arabic QA dataset (20k+ pairs) and a mobile chatbot application designed to provide accurate, unbiased information.

---

## Overview

Understanding Palestine’s geography and preserving its cultural identity is more important than ever. This project integrates machine learning and mobile development to offer a chatbot that can accurately answer questions about Palestine, from cities and landmarks to historical and demographic details.

---

## 📢 Latest Updates 

- **[Jan 2026] Dataset Revision:** We have updated the dataset to version 2.0.Update: We have restructured the dataset splits to enhance the training workflow and evaluation accuracy. The current version provides a more robust benchmark for the model.

---

### PalGeoLLM Data Splits (v2.0):
The dataset is partitioned as follows:
- **Training Set**: 18,277 question-answer pairs 
- **Development (Dev) Set**: 922 question-answer pairs 
- **Test Set**: 945 question-answer pairs 

---

## 🔧 How to Run

1. Clone the repo:
   ```bash
    git clone [https://github.com/SinaLab/PalGeoLLM.git](https://github.com/SinaLab/PalGeoLLM.git)    ```

2. Set up the **Flutter app**:
    
    ```bash
    cd app
    flutter pub get
    flutter run
    ```
    
3. The app communicates with a fine-tuned LLM hosted on Hugging Face to generate answers.
    

---

## Objectives

- Counter LLM biases against Palestine by fine-tuning on reliable Arabic sources.
    
- Build an accessible and educational mobile tool.
    
- Raise awareness of Palestine’s geographic and cultural identity.
    

---

## Support Palestine Through Technology

> “Technology is a tool — we chose to use it to preserve our truth.”
