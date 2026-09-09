🧠 SentimentPulse AI — Advanced NLP Sentiment & Emotion Analyzer

SentimentPulse AI is a state-of-the-art web-based Natural Language Processing (NLP) platform engineered to ingest text data from multiple sources, perform rigorous sentiment classification, map fine-grained human emotions using valence lexicons, visualize public opinion trends, and deliver actionable strategic business insights.

🌟 Core Features & Implementation of Rules

This project strictly implements and fulfills all 5 core NLP & data intelligence requirements:

📊 Text Classification (Positive, Negative, Neutral):

Live token parser analyzes input strings to evaluate polarity indices and model confidence scores in real-time.

🎭 NLP Lexicon-Based Emotion Mapping:

Employs NRC-style emotion lexicon matching to break down text into distinct psychological vectors: Joy, Anger, Surprise, Sadness, Fear, and Disgust.

🌐 Multi-Source Data Ingestion:

Simulates streaming and batch data pipelines across popular review and communication channels:

🛒 Amazon Reviews

💬 Social Media (Twitter / X)

📰 Global News Feeds

📈 Public Opinion & Sentiment Trends:

Dynamic charts powered by Chart.js tracking 7-day sentiment index fluctuations and global sentiment ratios (Positive / Neutral / Negative).

💼 Strategic Business Action Hub:

Automatically clusters negative and positive feedback to generate priority-driven operational strategies for Marketing, Product Engineering, and Public Relations.

📸 Preview & Architecture

┌────────────────────────────────────────────────────────┐
│                   SentimentPulse AI                    │
├──────────────────┬──────────────────┬──────────────────┤
│   Live Analyzer  │ Multi-Source Feed│  Trends & Ratio  │
│  (Lexicon Engine)│ (Amazon/Social)  │  (Chart.js Dash) │
└──────────────────┴──────────────────┴──────────────────┘


🚀 Quick Start / Installation

Because SentimentPulse AI is built with zero complex backend dependencies (pure HTML5, Tailwind CSS, and vanilla JavaScript), running it locally is instant!

Clone the repository:

git clone https://github.com/your-username/Sentiment_Analysis.git


Navigate to the project directory:

cd Sentiment_Analysis


Open the application:
Simply double-click Sentiment_Analysis.html or open it with any modern web browser (Chrome, Firefox, Edge, Safari). Alternatively, run a local development server using Python:

python -m http.server 8000


Then visit http://localhost:8000/Sentiment_Analysis.html in your browser.

🛠️ Tech Stack

Frontend UI: HTML5, Tailwind CSS (v3 CDN), FontAwesome Icons

Data Visualization: Chart.js

NLP Engine: Custom Token Frequency & Valence Lexicon Dictionary in JavaScript

📝 License

Distributed under the MIT License. See LICENSE for more information.
