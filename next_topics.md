

Classic ML 


- learn outliers
- revision of linear regression  and apply outliers and other feature enginerring techniques
- logistics regression
- neural net

(*For AI/LLM Engineer  —  rarely go deep on classical ML. But these are must-know:**

**High priority (conceptual understanding only):**
- Linear Regression + Logistic Regression — loss, gradient descent
- Bias-Variance tradeoff — very frequently asked conceptually
- Decision Trees + Random Forest — intuition, overfitting, feature importance
- Gradient Boosting (XGBoost) — know when to use it

**Medium priority (just know what/when to use):**
- KNN — simple intuition
- Naive Bayes — good for NLP context
- SVM — just high level, rarely asked deep

**Skip or very low priority for your target roles:**
- AdaBoost — rarely asked
- Deep classical stuff — not relevant

---

**For LLM/RAG/AI Engineer, care more about:**
- Overfitting, regularization, train/val/test split
- Evaluation metrics (precision, recall, F1, AUC)
- Embeddings, similarity search
- Transformer architecture basics

**Don't go deep on classical ML algorithms — 2-3 days max on the high priority ones is enough.**)

- finetuning - https://youtu.be/0MMAEwSmPDg?si=sz95iMjj7ngMtGTS

resource for linear and logistics regression(classification)
fine tuning yt link using hugging face and pytorch - https://youtu.be/bZcKYiwtw1I?si=CCRrakFf0BKRrleK
or 
fine tuning yt link - https://youtu.be/9yl6-HEY7_s?si=NCl8Mdhp7xvYMrfR

------

Revise/practice - next week

- L1 & L2 regularization (done)
- If dataset has more null values, doing with existing dataset (done)
    - Filling na/null values with mean values
    - Find the uniqueness and reduce it (not done ❌)
    - Remove by drop columns which are not much important to predict the price etc (done)
    - When to delete the column with inplace true (done)
    - check that titanic fastai - they added few more things to cover these na/null values (done)

------

Revise/practice - next another week

- Complete the left over regression house pricing 
- Write down complete flow of transformer, self-attention, encoder-decoder-attention
- Try desicion trees - Label encoding alternative of hot encoding if data has text categories like decision trees of google, masters degree
------

Revise/practice - next another another week

- **Cross validation** (K-fold) — how you evaluate fairly, must know
- Learn more about Bias-Variance tradeoff -> less variance, more bias etc (important)
- Train_test_split to split with random 20 -> existing data splitting into 80% of train data and 20% of test data
- If dataset has more null values, doing with **complex** dataset
    - Filling na/null values with mean values
    - Find the uniqueness and reduce it
    - Remove by drop columns which are not much important to predict the price etc
    - When to delete the column with inplace true
    - check that titanic fastai - they added few more things to cover these na/null values

------
AI architecture

- Transformer architecture
- Training Neural Networks -> basics or forward, backprop, loss, optimizers
- PyTorch becomes useful when you want to build/train:
- LLLM fine tuning using pytorch
- LLM Evaluation metrics & techniques like hallucination, BLEU, RAGAS

Low priority 
- LSTMs
- Image models (CNNs, GANs, RNNs)
- Custom deep learning architectures

------

AI 

- exploring other types of RAG
    - types of rag
    - graph rag
- Finetuning with unsloth, OLLMA, quantization and lora (because this process works good with large models as well)
    1. Normal fine-tuning on small model
    2. Learn LoRA
    3. Learn quantization
    4. Then use Unsloth for optimization
- MCP
- langsmith
- langgraph
- langchain
- crewai
- n8n
------

more information

Best medium-level dataset for  discussion:
House Prices - Advanced Regression Techniques (Kaggle)
Why good:
* Real-world dataset
* Missing values handling
* Feature engineering (outliers)
* Categorical encoding
* Correlation analysis
* Linear Regression + Ridge/Lasso comparison
* Evaluation using RMSE
You can say in:
“I worked on house price prediction using Linear Regression. I handled null values, categorical encoding, feature selection, scaling, and evaluated performance using RMSE.”