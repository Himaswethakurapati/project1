# SmartTrader: Machine Learning for Stock Price Prediction and Trading
#### Team Members

- **Member 1:**  
  Name: Prakhya Mylavaram  
  Email: [Your Email]  
  Student ID: [Your Student ID]  

- **Member 2:**  
  Name: Sai Pranavi Kurapati  
  Email: [Second Member's Email]  
  Student ID: [Second Member's Student ID]  

- **Member 3:**  
  Name: Himaswetha Kurapati  
  Email: [Third Member's Email]  
  Student ID: [Third Member's Student ID]

  
Application can be accessed at the following URL:  
**[SmartTrader App](https://smarttraderteam8-b1fb2d0e6121.herokuapp.com)**

---

#### Instructions

1. **Accessing the App:**
   - Open the provided URL in a web browser.
   - The app allows predictions for NVIDIA Corporation (NVDA) stock prices for the next 5 business days.

2. **Using the App:**
   - Input a date in the "Select Date" field.
   - Click on the "Predict" button to view the predicted high, low, and average prices, along with suggested trading strategies.

3. **Expected Outputs:**
   - A table displaying predictions for the next 5 business days.
   - A table showing trading strategies (BULLISH, BEARISH, or IDLE) based on the predictions.

4. **Deployment Details:**
   - Hosted on **Heroku** for real-time accessibility.
   - Backend is built using **Flask** with machine learning models serialized and integrated for prediction.

---

#### Build Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Himaswethakurapati/project1.git
   cd project1
   ```

2. **Set Up the Environment:**
   - Create a virtual environment:
     ```bash
     python3 -m venv venv
     source venv/bin/activate  # For Linux/Mac
     venv\\Scripts\\activate  # For Windows
     ```
   - Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the App Locally:**
   - Execute the following command:
     ```bash
     python app.py
     ```
   - Access the app locally at `http://127.0.0.1:5000`.

4. **Deploy to Heroku (Optional for Verification):**
   - Ensure Heroku CLI is installed.
   - Log in to Heroku:
     ```bash
     heroku login
     ```
   - Deploy the app:
     ```bash
     git push heroku main
     ```
