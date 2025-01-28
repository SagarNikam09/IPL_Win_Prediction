# IPL Win Predictor

A machine learning application that predicts the winning probability of IPL matches using Streamlit.

## Features

- Predict win probability for any IPL match scenario
- Select batting and bowling teams
- Choose host city
- Input match parameters like target, current score, overs, and wickets
- Real-time probability calculation

## Tech Stack

- Python 3.11
- Streamlit
- Scikit-learn
- Pandas
- Pickle

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/ipl-win-predictor.git
cd ipl-win-predictor
```

2. Create and activate virtual environment

```bash
python -m venv mlenv
mlenv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

### Usage
1. Start the Streamlit app:
```bash
streamlit run app.py
```

2. Input the following parameters:

* Select batting team
* Select bowling team
* Choose host city
* Enter target score
* Enter current score
* Enter overs completed
* Enter wickets fallen

3. Click on 'Predict Probability' to see the result

### Project Structure
```bash 
├── app.py              # Streamlit application
├── pipe.pkl           # Trained machine learning model
├── requirements.txt   # Project dependencies
└── README.md         # Project documentation
```

### Data Description
* Teams included: 8 IPL teams
* Cities: 29 IPL venues worldwide
* Features used for prediction:
    * Batting team
    * Bowling team
    * City
    * Target
    * Current score
    * Overs completed
    * Wickets fallen

### License

This project is licensed under the MIT License.