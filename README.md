# FAiNANCE - AI-Powered Financial Intelligence Platform 🚀

FAiNANCE is a comprehensive financial management platform that combines personal finance tracking, investment analysis, and AI-powered insights to help users make better financial decisions.

## Features ✨

- **Expense Tracking** 💰
  - Log and categorize daily expenses
  - Visual analytics and spending patterns
  - Monthly budget alerts
  - Expense trend analysis

- **Investment Tools** 📈
  - SIP (Systematic Investment Plan) Calculator
  - Real-time stock market data
  - Personal stock watchlist
  - Market indices tracking

- **Financial Goals** 🎯
  - Set and track financial goals
  - Progress monitoring
  - Automated savings recommendations
  - Goal-based investment planning

- **AI-Powered Features** 🤖
  - Personalized financial advice
  - Interactive AI chatbot for financial queries
  - Expense analysis insights
  - Investment recommendations

## Technology Stack 🛠️

- **Backend**: Flask 3.0.0
- **Database**: SQLAlchemy with SQLite
- **Frontend**: Bootstrap 5, Plotly.js
- **AI Integration**: Google Gemini AI
- **Authentication**: Flask-Login
- **Market Data**: Alpha Vantage API, Yahoo Finance

## Setup Instructions 🔧

1. Clone the repository:
```bash
git clone 
cd FAiNANCE
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables in `.env` file:
```
SECRET_KEY=your_secret_key
DATABASE_URL=sqlite:///FAiNANCE.db
GOOGLE_API_KEY=your_google_api_key
ALPHA_VANTAGE_API_KEY=your_alphavantage_api_key
```

5. Initialize the database:
```bash
flask db upgrade
```

6. Run the application:
```bash
python app.py
```

The application will be available at `http://localhost:5000`

## API Keys Required 🔑

- Google API key for Gemini AI integration
- Alpha Vantage API key for stock market data (free tier available)

## Project Structure 📁

```
FAiNANCE/
├── app.py              # Application entry point
├── src/
│   ├── models/         # Database models
│   ├── routes/         # API routes and views
│   ├── services/       # Business logic
│   └── utils/          # Helper functions
├── static/
│   ├── css/           # Stylesheets
│   ├── js/            # JavaScript files
│   └── img/           # Images
├── templates/          # HTML templates
```
