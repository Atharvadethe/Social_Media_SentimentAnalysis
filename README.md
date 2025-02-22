# 📊 Social Media Sentiment Dashboard

We built a platform to analyze public sentiment on social media (Twitter, Reddit) around a topic or event. The goal was to use scraping, NLP, and data visualization to generate insights that could be leveraged for targeted advertising.

## 🚀 Features

- **Clarity Dashboard:** A real-time graphical representation of positive vs. negative sentiments using bar charts, pie charts, and trend graphs. The scraped tweets and Reddit posts are displayed alongside a sentiment score for transparency.
- **Clarity PR:** Businesses can upload a file containing customer reviews, and our system will classify them as positive, negative, or neutral, with visual insights.
- **Trending Topic Analysis:** Businesses can search for any trending topic. We provide a summary along with article sources, enabling companies to capitalize on trends for profitability.
- **AI Chatbot:** A chatbot to answer queries and assist users in gaining deeper insights.

## 🛠️ Tech Stack

- **Backend:** Django, Python  
- **Frontend:** Tailwind CSS, JavaScript  
- **APIs:** Tavily, Reddit Scraper, Twitter Scraper  
- **NLP:** NLTK (Sentiment Analysis), Scikit-learn (TF-IDF)  
- **Database:** SQLite (default) 

## 📦 Install and Run

To get started, clone the repository, set up a virtual environment, install dependencies, configure your environment variables, run migrations, and start the development server. Here's how:
```bash
git clone https://github.com/Atharvadethe/Social_Media_SentimentAnalysis.git
cd <project_directory>
```

```
pip install -r requirements.txt
```
```bash
python manage.py migrate
python manage.py runserver 3000
```
## 🔴 Important
- Make sure you have all the proper api keys in .env file.
- Add proper callback URLs while configuring the auth 0 application in auth 0  dashboard.

## 📚 Acknowledgements
This project is inspired by various tutorials and resources available online.