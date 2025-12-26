# Bulldozer Price Prediction API

This project is a **FastAPI web service** for predicting bulldozer prices using a trained RandomForestRegressor model.  
It exposes a REST API with endpoints for health checks and predictions.

---

##  Features
- Built with **FastAPI** and **Uvicorn**
- Loads a pre‑trained `RandomForestRegressor` model (`bulldozer_price_model.joblib`)
- `/` root endpoint for status check
- `/predict` endpoint for price prediction

---

##  Project Structure
