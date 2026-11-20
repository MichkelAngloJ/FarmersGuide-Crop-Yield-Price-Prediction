# FarmersGuide - Crop Yield & Price Prediction

My final-year B.E. (ECE) project (2023): a web app that helps farmers predict **crop yield** and **crop market price** using machine-learning models.

## Features
- Sign up / log in with email OTP verification
- Crop yield prediction (ensemble Random Forest model)
- Crop price prediction
- Contact form that emails the team

## Tech stack
Angular 15 | Flask (REST API) | MongoDB Atlas | scikit-learn | pandas | joblib

## Project structure
| Folder | What's in it |
|---|---|
| `Angular/` | Frontend (Angular 15) |
| `Flask/` | Backend API; trained models are in `Flask/static/` |
| `notebooks/` | Jupyter notebooks used to explore the data and train the models |
| `data/` | Datasets used for training |
| `models/` | Other trained model versions |
| `docs/` | Project report, abstract, review presentations and screenshots |

## Run it locally
**Backend**
```bash
cd Flask
pip install -r requirements.txt
# set MONGO_URI, MAIL_USERNAME, MAIL_PASSWORD, CONTACT_EMAIL (see .env.example)
python app.py
```

**Frontend**
```bash
cd Angular
npm install
npx ng serve
```
Then open http://localhost:4200

## Demo
Demo video: _add link here_

## Team
Built as a team project together with [ponbalaji2001](https://github.com/ponbalaji2001) ([team repo](https://github.com/ponbalaji2001/Crop_Recommendation_and_Price_Prediction_Web_App)).