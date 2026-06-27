###   Research and Projects

<table width="100%"><tr>
<td align="left"><b>n8n Daily Taiwan Stock Push: Yahoo Finance × TWSE × Groq Llama 3.3 AI</b></td>
<td align="right"><i>Jun. 2026 – Jul. 2026</i></td>
</tr></table>

Repository: [n8n-Taiwan-Stock-Push](https://github.com/brianlab0/n8n-Taiwan-Stock-Push)
- Automated daily Taiwan-stock briefing emailed every trading day after market close, built on the **n8n** visual workflow engine and self-hosted on **Docker**.
- Aggregates live quotes for 45+ stocks across 20+ sectors (**Yahoo Finance**), three-major-institution net buy/sell (**TWSE**), MA/RSI technicals, and market news (**Tavily**).
- **Groq Llama 3.3 70B** generates 10 buy + 10 sell diversified recommendations (never concentrated in large-cap weights), per-stock rationale, per-headline news digests, and a daily finance-term tip — rendered as a clean **LaTeX-style HTML email** via **Gmail SMTP**.
- Trading-day-aware scheduling detects market sessions from the index timestamp and automatically skips weekends and national holidays.

<table width="100%"><tr>
<td align="left"><b>n8n Full-Stack Automation: YouTube Comment Monitor × LINE Bot × Gemini AI</b></td>
<td align="right"><i>May 2026 – Jun. 2026</i></td>
</tr></table>

Repository: [n8n-YouTube-Comment-Bot](https://github.com/brianlab0/n8n-YouTube-Comment-Bot)
- End-to-end automation pipeline integrating **LINE Messaging API**, **YouTube Data API v3**, and **Google Gemini AI** via **n8n** visual workflow engine.
- Workflow 1 — **LINE → AI → Sheets**: Conversational rule setup; Gemini parses natural-language messages into structured JSON and writes rules into Google Sheets.
- Workflow 2 — **Scheduled Auto-Reply**: Polls YouTube comments every 3 minutes; keyword-matched comments get auto-replied via API, and Gemini-generated notifications are pushed to LINE in real time.
- Self-hosted on **Docker + ngrok** for full data privacy and zero recurring cost, eliminating dependence on n8n Cloud.

<table width="100%"><tr>
<td align="left"><b>National Science and Technology Council Undergraduate Research Project</b><br/>
<i>An Empirical Study on Multi-Level Momentum and Liquidity Volatility Using Machine Learning</i></td>
<td align="right"><i>Jul. 2025 – Feb. 2026</i></td>
</tr></table>

Repository: [Taiwan-Stock-Forecasting-Research](https://github.com/brianlab999/Taiwan-Stock-Forecasting-Research)
- Built ML-based quantitative trading strategies on **Taiwan stock market data from Jan. 1999 – Feb. 2025**.
- Nonlinear models outperformed linear regression on prediction and backtest returns **by ~50%**.
- Engineered a multi-level factor set: short-/long-term momentum, momentum change, max single-period return, return volatility.
- XGBoost, LightGBM, Random Forest, GBRT, NN delivered the best accuracy and cumulative returns vs. **TWII**.
- Presented at **TRIA 2025** (Taiwan Risk and Insurance Annual Conference and International Symposium).

<table width="100%"><tr>
<td align="left"><b>HFSLS-PSO-BIGRU Stock Prediction Model</b></td>
<td align="right"><i>Sept. 2025 – Jan. 2026</i></td>
</tr></table>

Repository: [Taiwan-Stock-Forecasting-Research](https://github.com/brianlab999/Taiwan-Stock-Forecasting-Research)
- HFSLS-PSO-BIGRU improves R² by +2.394 and reduces MSE by 97.1% vs baseline BIGRU.
- **HFSLS feature selection contributes 97% of total performance gain.**
- Validated cross-industry generalization: stable performance on defensive and tech stocks, and effective capture of cyclical volatility patterns.
- Demonstrates strong robustness and consistent predictive performance across different market regimes.

<table width="100%"><tr>
<td align="left"><b>3C Shopping Assistant — LINE Bot</b></td>
<td align="right"><i>Mar. 2025 – May 2025</i></td>
</tr></table>

Repository: [3C-Shopping-Assistant-Linebot](https://github.com/brianlab999/3C-Shopping-Assistant-Linebot)
- Multi-feature LINE chatbot integrating **Flask + LINE Messaging API + SQLite** for 3C product price lookup, tech news, AI consultation, and customer feedback.
- Web-scraped real-time prices from multiple 3C retailers (傑昇通信, 地標網通, 創捷國際, 台灣大哥大) using **requests + BeautifulSoup**.
- Runtime model switching between **OpenAI GPT-3.5** and a locally-hosted **Taide LLM** (Ollama), via in-chat button menus.

<table width="100%"><tr>
<td align="left"><b>Steam Top Sellers Scraping and Trend Analysis</b></td>
<td align="right"><i>Jan. 2025 – Mar. 2025</i></td>
</tr></table>

Repository: [Web-Scraping-with-Selenium](https://github.com/brianlab999/Web-Scraping-with-Selenium) · [Demo Video](https://youtu.be/1XpNq_qj1w4)
- Built a **Selenium** scraper for the Steam Top 100 chart (Taiwan region) across 2024–2026, producing a 120+ weekly-snapshot dataset (~12,000 records).
- Developed an **Tkinter GUI** with pandas / Matplotlib for free-vs-paid ratio analysis, yearly rankings, three-year business-model trend, and game-level timeline drill-down.

<table width="100%"><tr>
<td align="left"><b>Web Application with SQLite Back-End</b></td>
<td align="right"><i>Dec. 2024 – Feb. 2025</i></td>
</tr></table>

Repository: [Web-Application-with-SQLite-Back-End](https://github.com/brianlab999/Web-Application-with-SQLite-Back-End) · [Demo Video](https://youtu.be/-8x2bmUEOtM)
- Full-stack web app (**Node.js + Express + SQLite**) wired to the [Mövenpick Café front-end](https://github.com/brianlab999/Movenpick-Cafe-front-end).
- RESTful API with parameterized SQL queries; CRUD operations with **100% data integrity** and **<200 ms** response time.

<table width="100%"><tr>
<td align="left"><b>QB Music Education Front-End</b></td>
<td align="right"><i>Oct. 2024 – Nov. 2024</i></td>
</tr></table>

Repository: [QB-Music-front-end](https://github.com/brianlab999/QB-Music-front-end)
- Multi-page front-end website (HTML/CSS/JS + Bootstrap CDN) for a music education brand: news, brand story, instruments, members area, classroom map, charity, and franchise pages.

<table width="100%"><tr>
<td align="left"><b>Mövenpick Café Front-End</b></td>
<td align="right"><i>Aug. 2024 – Sept. 2024</i></td>
</tr></table>

Repository: [Movenpick-Cafe-front-end](https://github.com/brianlab999/Movenpick-Cafe-front-end)
- Multi-page restaurant website (HTML/CSS/JS) covering menus, set meals, reservations, and brand introduction.
- Serves as the front-end layer for the SQLite full-stack reservation system above.

---

###   Tech Stack

**Languages** &nbsp; `Python` `R` `SQL` `JavaScript` `HTML` `CSS`  
**Machine Learning** &nbsp; `scikit-learn` `XGBoost` `LightGBM` `GBRT` `Random Forest`  
**Deep Learning** &nbsp; `TensorFlow` `PyTorch` `Neural Networks` `BIGRU`  
**Data Science** &nbsp; `pandas` `NumPy` `Matplotlib`  
**Statistics** &nbsp; `Regression` `Time Series` `Statistical Learning` `Feature Engineering`  
**Data Engineering** &nbsp; `Apache Airflow` `Elasticsearch` `ETL` `REST API` `Git`  
**Web Scraping** &nbsp; `Selenium` `ChromeDriver` `BeautifulSoup` `Requests`  
**Web and Backend** &nbsp; `Flask` `Node.js` `Express` `SQLite`  
**Workflow Automation** &nbsp; `n8n` `Webhook` `Cron` `Schedule Trigger`  
**DevOps and Infrastructure** &nbsp; `Docker` `docker-compose` `ngrok`  
**LLM and Messaging** &nbsp; `OpenAI API` `Ollama` `Google Gemini API` `LINE Messaging API`  
**Cloud APIs** &nbsp; `Google Sheets API` `YouTube Data API v3` `OAuth 2.0`  
**Desktop GUI** &nbsp; `Tkinter`

---

###   Technical Certifications

- **Python Programming Certification** — *Silicon Stone Education*
- **AI and Machine Learning Program** — *National Taiwan University*
- **Google Analytics Certification**

---

<p align="center"><i>Open to collaboration on data science, quantitative finance, and digital finance projects.</i></p>
