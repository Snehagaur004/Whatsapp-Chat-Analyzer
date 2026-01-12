# 📱 WhatsApp Chat Analysis

**Project Overview:-**

This project is a web application that analyzes WhatsApp chat data to provide insights into user activity, messaging trends, and conversation patterns.

By simply exporting your WhatsApp chat (individual or group chat), this app helps visualize:

* 🕒 *Activity trends over time –* see when chats are most active

* 📊 *Most active users in a group –* track who’s talking the most

* 💬 *Most common words and emojis –* discover recurring messages and emotions

* 🏆 *Peak chat hours –* identify your busiest chat times

* ✨ *And much more… –* including shared links, media, and chat statistics

It’s built to be user-friendly, interactive, and visually appealing.

**Features:-**

* 💡 Works with both individual and group chats

* 📊 Generates activity timelines, most active participants, and emoji usage

* ☁️ Creates word clouds to highlight frequently used words

* 📈 Offers visualizations like bar charts and line plots to explore trends

**Requirements:-**

To run this project, the following Python libraries are required:

* **re –** for text processing

* **pandas –** for data manipulation 📊

* **collections –** for counting word and emoji frequency 🧮

* **seaborn –** for advanced statistical plots 📈

* **urlextract –** to extract URLs 🌐

* **matplotlib –** for visualization 🎨

* **wordcloud –** to generate word clouds ☁️

* **streamlit –** to build the interactive web app 💻

You can install them using:
````
pip install pandas seaborn matplotlib wordcloud urlextract streamlit re
````
**How It Works:-**

**1.** Export your WhatsApp chat as a .txt file.

**2.** Upload the chat file into the web app.

**3.** The app cleans and processes the data, extracting messages, dates, users, and emojis.

**4.** Visualizations and analytics are generated automatically for:

  * Daily, monthly, and weekly activity

  * Most active users

  * Frequently used words and emojis

  * Shared links and media

**Tools & Technologies:-** 

* Python 3.8 – Core programming language 🐍

* PyCharm – IDE with a virtual environment for development 💻

* Streamlit – For creating the interactive web interface 🌐

* Seaborn & Matplotlib – For generating plots and charts 📊

* WordCloud – For visual representation of commonly used words ☁️

**How to Run:-**

**1.** *Install dependencies*

**2.** *Launch the Streamlit app:*
````
streamlit run app.py
````
