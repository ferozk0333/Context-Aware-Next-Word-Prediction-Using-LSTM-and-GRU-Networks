# Context-Aware Next Word Prediction Using LSTM and GRU

## Overview
This project implements a **Next Word Prediction** system using **LSTM** and **GRU** networks, trained on **Shakespeare’s Hamlet**. It leverages deep learning techniques such as tokenization, sequence padding, and softmax-based word prediction. The model is built using **TensorFlow** and deployed via **Streamlit** for real-time text generation.

## Project Workflow  
1. **Data Preprocessing**: Tokenization, text normalization, sequence generation, and padding  
2. **Model Training**: LSTM/GRU-based RNN architecture with embedding, recurrent, and dense layers  
3. **Evaluation**: Performance comparison between LSTM and GRU  
4. **Deployment**: Streamlit-based web application  

## Model Architecture  
![image](https://github.com/user-attachments/assets/c0197f17-9c4e-4d69-96c8-7d3f64424592)


## Installation & Setup  
Clone the repository and install dependencies:

```bash
git clone https://github.com/ferozk0333/Context-Aware-Next-Word-Prediction-Using-LSTM-and-GRU-Networks.git
cd Context-Aware-Next-Word-Prediction-Using-LSTM-and-GRU-Networks
pip install -r requirements.txt
```

Training the Model
To train the model, run:
```bash
python train.py
```

Prediction Example
```bash
input_text = "To be or not to be"
next_word = predict_next_word(model, tokenizer, input_text, max_sequence_length)
print("Next word prediction:", next_word)

```


Results & Observations
- LSTM achieves higher accuracy but takes longer to train.
- GRU is faster but slightly less accurate for longer sequences.
- Training for 100+ epochs improves prediction quality.
