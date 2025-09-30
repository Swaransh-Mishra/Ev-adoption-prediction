# 🔮 EV Adoption Forecasting

A **machine learning powered web app** that forecasts **Electric Vehicle (EV) adoption trends** for counties in Washington State.  
- Built with **Streamlit**, **scikit-learn**, and **Matplotlib**, this tool helps visualize historical adoption and predicts the next 3 years of EV growth.

---

## 🚀 Features

- 📊 **County-level forecasting** of EV adoption over the next 36 months  
- 🔍 **Interactive selection** of counties for single or multi-county comparison  
- 🟢 **Dynamic cumulative plots** (historical + forecast)  
- 📈 **Growth percentage summaries** for easy interpretation  
- 🎨 **Custom styling** with dark-mode charts and gradient background  
- 🌐 **Deployed on Streamlit Cloud**  

---

## 📂 Project Structure

EV_Adoption_Forecasting/
├── app.py                        # Streamlit application
├── forecasting_ev_model.pkl      # Trained ML model
├── preprocessed_ev_data.csv      # Historical EV adoption data
├── ev-car-factory.jpg            # Header image
├── EV_Adoption_Forecasting.ipynb # Notebook for model building
└── README.md                     # Project documentation


---

## ⚙️ Tech Stack

- **Frontend / Deployment**: [Streamlit](https://streamlit.io/)  
- **Backend / ML**: scikit-learn, pandas, numpy, joblib  
- **Visualization**: Matplotlib  
- **Data**: Washington State county-level EV adoption dataset (preprocessed)  

---

## 📥 Installation

Clone this repository and install dependencies:

git clone https://github.com/Swaransh-Mishra/EV_Adoption_Forecasting.git
cd EV_Adoption_Forecasting
pip install -r requirements.txt


▶️ Running Locally

Run the Streamlit app with:

streamlit run app.py


Then open your browser at:
👉 http://localhost:8501


🌐 Live Demo

🚘 Try it here: EV Adoption Forecasting App


📊 Example Output

- 📈 Cumulative EV adoption forecast for a county

- 🔄 Multi-county comparison over 3 years

- 📉 Percentage growth insights

👨‍💻 Author

Swaransh Mishra
🌐 GitHub
 • LinkedIn
