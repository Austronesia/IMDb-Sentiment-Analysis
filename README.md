# Sentiment Analysis on IMDb Reviews 🎭  
### **Natural Language Processing - Text Classification**

## 📌 Overview  
This project explores **sentiment analysis** using **Natural Language Processing (NLP)** on the **IMDb dataset**, which consists of movie reviews labeled as **positive (1) or negative (0)**.  
The objective is to train a model that can **automatically classify** whether a given review expresses a positive or negative sentiment.  

## 🔍 **Approach**  
We implement and compare two types of **word embeddings** with different models:  

1. **TF-IDF Embedding** (Text mapped to a frequency-based vector)  
   - 📌 **Naive Mixture of Experts (MoE) Model**  
   - 📌 **Logistic Regression**  

2. **Word2Vec Embedding** (Each word mapped to a dense vector capturing meaning)  
   - 🧠 **Convolutional Neural Network (CNN)**  
   - 🔄 **Long Short-Term Memory (LSTM) Network**  

## 📊 **Results**  
🚀 (Here, add any key insights, accuracy scores, confusion matrices, or plots to make it more visually appealing!)  

## ⚙️ **Installation & Execution**  
1. Clone this repository:  
   ````bash ```
   git clone https://github.com/Austronesia/Text-Classification-IMDB.git
   cd Text-Classification-IMDB````
2. Install dependencies:
   ````bash ```
   pip install -r requirements.txt````
3. Run the Jupyter Notebook:
   ````bash ```
   jupyter notebook````

## 📁 Project Structure
├── notebooks/                # Jupyter Notebooks with analysis
├── models/                   # Saved trained models
├── results/                  # Plots & evaluation metrics
├── README.md                 # Project documentation
└── requirements.txt          # Dependencies

## Next Steps and Improvements
- Try additional embeddings (FastText, BERT)
- Tune hyperparameters for CNN & LSTM
- Try a Mixture of Experts model with a CNN and a LSTM expert

