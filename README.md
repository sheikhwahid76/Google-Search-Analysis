# 📊 Cloud Computing Trend Analysis with Google Trends

This project analyzes the popularity and interest in Cloud Computing using Google Trends data, powered by the pytrends API. It visualizes interest over time, identifies top regions, and retrieves related search queries.

## 🔧 Features

- Fetches and analyzes 12 months of Google Trends data for "Cloud Computing".
- Compares interest for a specific time period (Jan 2024).
- Identifies the top regions where "Cloud Computing" is most searched.
- Visualizes data using matplotlib.
- Retrieves related search queries and keyword suggestions from Google Trends.

## 🛠 Tools and Libraries Used

- Python 3.7+
- [Pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [pytrends](https://github.com/GeneralMills/pytrends)

## 📁 Project Structure


cloud-computing-trends/
├── trend_analysis.py      # Main Python script
├── requirements.txt       # Dependencies
└── README.md              # Project documentation

▶️ How to Run
Clone the Repository

git clone https://github.com/your-username/cloud-computing-trends.git
cd cloud-computing-trends
Install Dependencies


pip install -r requirements.txt
Run the Script

python trend_analysis.py


✅ Requirements
Python 3.7 or above

Active internet connection (to access Google Trends)

Required packages listed in requirements.txt:

nginx

pandas
matplotlib
pytrends


📌 Notes
Add a short delay (time.sleep) after payload requests to avoid being rate-limited by Google Trends.

The pytrends module is unofficial and may occasionally break due to changes in the Google Trends site.

The script uses matplotlib for visualizing interest by region in bar chart format.
