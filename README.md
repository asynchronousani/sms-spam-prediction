# SMS Spam Prediction Project 📱💬

This project is aimed at predicting whether an SMS message is spam or not using the Random Forest algorithm. The project includes a Streamlit web application for easy interaction and visualization of the prediction results.

## Getting Started 🚀

To run the application, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/asynchronousani/sms-spam-prediction.git
```

2. Navigate to the project directory:

```bash
cd sms-spam-prediction
```

3. Install the required dependencies. It's recommended to use a virtual environment:

```bash
pip install -r requirements.txt
```
   
4. Run the Streamlit application:

```bash
streamlit run app.py
```

5. Access the application in your browser at `http://localhost:8501`.

## Usage ℹ️

Once the application is running, you will be presented with an interface where you can enter an SMS message. After entering the message, click on the "Predict" button to see whether the message is classified as spam or not. The application will display the prediction result along with the probability score.

## Algorithm Used 🧠

This project utilizes the Random Forest algorithm for its predictive modeling. Random Forest is an ensemble learning method that operates by constructing a multitude of decision trees during training and outputting the mode of the classes (classification) or the mean prediction (regression) of the individual trees.

## Data 📊

The project uses a labeled dataset containing SMS messages, with each message labeled as either "spam" or "ham" (not spam). The dataset is split into training and testing sets to train and evaluate the performance of the model.

## Test Results 📊

### Spam Message Prediction
![Spam Message Prediction](images/Spam.jpg)

### Not Spam Message Prediction
![Not Spam Message Prediction](images/NotSpam.jpg)

## **Contributing 🤝:**
Contributions to the project are welcome! Whether it's improving the model's performance, adding new features, or optimizing the code, feel free to submit pull requests.
