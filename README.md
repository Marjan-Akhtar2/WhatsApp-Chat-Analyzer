# WhatsApp Chat Analyzer

An interactive Python data visualization web application built with **Streamlit**, **Pandas**, **Seaborn**, and **Matplotlib**. This tool converts exported WhatsApp chat logs into clean, readable dashboards—offering deep insights into communication patterns, active hours, user dynamics, word usage, and emoji trends.

---

## Features

* **Overall & Individual Analysis:** Switch seamlessly between group-level stats and individual participant metrics.
* **Key Metrics Dashboard:** Instant overview of total messages, word count, shared media, and links shared.
* **Timelines:** Monthly and daily message frequency timelines to track group activity over time.
* **Activity Maps:** Visual breakdown of the busiest days of the week, active months, and hourly activity heatmaps.
* **Most Active Users:** Identifies top contributors in group chats through interactive bar plots and percentage share tables.
* **Word Cloud & Common Words:** Generates custom word clouds and top 20 most frequent words (filtering out Hinglish/English stop words).
* **Emoji Breakdown:** Parses and visualizes the most frequently used emojis with pie charts and detailed data tables.

---

## Tech Stack

* **Language:** Python 3.10+
* **Web Framework:** Streamlit
* **Data Processing:** Pandas, Regex (`re`)
* **Data Visualization:** Matplotlib, Seaborn, WordCloud
* **Utilities:** Emoji, URLExtract

---

## Quick Start

### 1. Clone the Repository
```bash
git clone [https://github.com/Marjan-Akhtar2/WhatsApp-Chat-Analyzer.git](https://github.com/Marjan-Akhtar2/WhatsApp-Chat-Analyzer.git)
cd WhatsApp-Chat-Analyzer