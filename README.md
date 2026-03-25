# Investment Management API 📈

A professional Back-end API developed to help investors manage their portfolios, track assets, and monitor dividends.

### 🛠 Technologies
- **Language:** Python
- **Framework:** FastAPI
- **Database:** SQLite
- **Documentation:** Swagger UI

### 🚀 Features
- Register and track stock and REIT (FIIs) purchases/sales.
- Automatic average price calculation.
- Dividend and earnings history tracking.
- Interactive documentation via Swagger.

### 💻 How to run
1. Clone the repository.
2. Create a virtual environment: `python -m venv venv`.
3. Activate it: `venv\Scripts\activate` (Windows) or `source venv/bin/activate` (Linux/Mac).
4. Install requirements: `pip install fastapi uvicorn`.
5. Start the server: `uvicorn main:app --reload`.
6. Access the docs at: `http://127.0.0.1:8000/docs`.
