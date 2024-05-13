# Stock Portfolio Suggestion Engine

## Project Description

The Stock Portfolio Suggestion Engine utilizes various investment strategies, such as ethical investing, value investing, growth investing, index investing, and quality investing. It suggests optimal investment options based on the user's input of the investment amount. The user interface presents a detailed report of the recommended stock portfolio, providing a seamless experience.

### Demo of the App

<!-- Watch a demonstration of the app on YouTube: [Stock Portfolio Suggestion Engine Demo](https://www.youtube.com/watch?v=iDp8JD8DF80) -->

![App Demo](https://github.com/KopalliAditya/Stock-Suggestion/blob/main/results-thumbnail.PNG)

[YouTube video](https://www.youtube.com/watch?v=KbkJqe3dmPw)

### Features

1. User inputs the investment amount in USD (Minimum: $5000 USD).
2. Users can choose one or two investment strategies from the following options:
    - Ethical Investing
    - Growth Investing
    - Index Investing
    - Quality Investing
    - Value Investing
3. The engine assigns specific stocks or ETFs for the selected investment strategy. For example:
4. Index Investing strategy could map to ETFs like:
    - Vanguard Total Stock Market ETF (VTI)
    - iShares Core MSCI Total Intl Stk (IXUS)
    - iShares Core 10+ Year USD Bond (ILTB)
5. Ethical Investing strategy might map to individual stocks like:
    - Apple (AAPL)
    - Adobe (ADBE)
    - Nestle (NSRGY)
6. Each strategy corresponds to at least three different stocks or ETFs.
7. The suggestion engine provides:
    - The selected stocks based on inputted strategies.
    - Allocation of funds to purchase the suggested stocks.
    - Real-time values of the overall portfolio (updated regularly).
    - A weekly trend of the portfolio value, including a 5-day history.

### Technologies Utilized

- Flask
- Python
- React
- Node.js
- JavaScript
- HTML5
- CSS3
- Bootstrap
- Ant Design
- Heroku
- REST
- IEX Stock API
- TradingView Market Overview Widget

### Running the Backend
1. Navigate to the `backend` directory:

    ```bash
    cd backend
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask app:

    ```bash
    python stock-suggestion-server.py
    ```

   The backend server should be running at http://127.0.0.1:5000

### Running the Frontend
1. Navigate to the `frontend` directory:

    ```bash
    cd frontend
    ```

2. Install the required dependencies:

    ```bash
    npm install
    ```

3. Start the React app:

    ```bash
    npm start
    ```

   The frontend should be accessible at http://localhost:3000.

Open your web browser and visit http://localhost:3000 to interact with the Stock Portfolio Suggestion Engine.



### Team Members

- Abhishek Mohanty
- Aditya Kopalli
- Vishwa Tejendra Pernapati
- Vishnu V
