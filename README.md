# **Predicting Instagram Hashtag Frequency Using LSTM**

---

## **Project Overview**

This project focuses on **predicting the future usage frequency of a specific Instagram hashtag** — specifically **#mentalhealth** — using time-series forecasting with an LSTM (Long Short-Term Memory) neural network.

> **Note:**  
> We are **not** predicting *which* hashtags will trend next. Instead, we predict *how often* one particular hashtag (#mentalhealth) will be used the next day based on its past usage data.

---

## **Why This Project?**

- Track public interest and conversations around mental health on Instagram.  
- Help content creators and marketers plan campaigns effectively.  
- Analyze engagement patterns and anticipate hashtag popularity.

---

## **How It Works**

1. **Data Preparation:**  
   Collect historical daily frequency data of the #mentalhealth hashtag.

2. **Sequence Creation:**  
   Create input sequences of 7 consecutive days’ data to predict the 8th day.

3. **Model Architecture:**  
   Train an LSTM neural network to learn temporal patterns in the data.

4. **Prediction:**  
   Use the trained model to forecast the hashtag’s usage frequency for the next day.

---

## **Tech Stack**

- **Python**  
- **TensorFlow/Keras** — For building and training the LSTM model  
- **NumPy & Pandas** — For data processing  
- **Matplotlib/Seaborn** — For visualization  
- **Google Colab** — Cloud-based training environment

---

## **Usage**

1. Clone this repository  
2. Prepare your dataset with daily hashtag frequencies  
3. Run the training notebook or script to train the model  
4. Use the trained model to predict future hashtag frequency

---

## **Project Structure**

/data

hashtag_frequency.csv # Time-series data of hashtag counts
/model

lstm_model.keras # Saved LSTM model file
/notebooks

training_and_prediction.ipynb # Notebook for training and testing
README.md # Project description and instructions


---

## **Future Enhancements**

- Extend to multiple hashtags prediction simultaneously  
- Implement hashtag trend discovery (predict which hashtags will trend)  
- Deploy as a web app or API for real-time predictions

---

## **Contributing**

Contributions, issues, and feature requests are welcome! Feel free to fork and submit pull requests.

---

## **License**

This project is licensed under the MIT License.

---

## **Author**

Uday Trivedi — Student at VIT Chennai  
Contact: udaytrivedi0012@gmail.com

---

**Thank you for your interest in this project!**
