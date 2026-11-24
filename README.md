### Hi there! 👋 I'm Shadi. 

I'm a software engineer with experience in data analytics, Automation developer and Front-End Development (using JavaScript and Vue.js). I like to take a real question, find the answer in the data, and present it so anyone can follow it. Alongside data analysis, I build automation: scripts that clean up spreadsheets, scheduled jobs, small data pipelines and the CI/CD that ships them.

### What I'm working on
- Data analysis projects on real data
- Data pipelines with SQL, PostgreSQL and dbt
- Workflow automation with Google Apps Script and GitHub Actions

### Projects

[otto-cart-recovery](https://github.com/ShadiShirinbeik/otto-cart-recovery) · [Live presentation](https://shadishirinbeik.github.io/otto-cart-recovery/)
Cart abandonment analysis on real OTTO e-commerce data (12.9M users). A 1M-user sample goes through PostgreSQL and a dbt pipeline (staging, prep, mart) into Python notebooks, a Tableau dashboard and an interactive web presentation. 57% of users who add to cart never order. A target group of 26,919 high-intent abandoners (3+ cart adds, 4+ active days) is best reminded about one hour after their cart.

**[beauty-returns-triage-agent](https://github.com/ShadiShirinbeik/beauty-returns-triage-agent)**
Make scenario that takes customer return requests from a Google Form, uses Gemini to classify the reason and sentiment, and routes each case to auto-approve, a photo request by email, or a Slack escalation. Every case is logged in Google Sheets, failed runs retry with Slack alerts, and a nightly TypeScript job on GitHub Actions flags stuck or overdue cases.

**[beauty-orders-automation](https://github.com/ShadiShirinbeik/beauty-orders-automation)**
Google Apps Script that checks an orders sheet for duplicate and incomplete rows, rebuilds six KPIs and emails a 7 AM digest. Pull requests get a syntax check, and merges to main deploy through clasp and GitHub Actions.

**[dbt-texas-freeze-2021](https://github.com/ShadiShirinbeik/dbt-texas-freeze-2021)**
A Python loader pulls daily weather for five Texas airports from the Meteostat API into PostgreSQL. A dbt pipeline (staging, prep, mart) with schema tests then joins it with about 100,000 departures. During Winter Storm Uri, cancellations went from about 1% to 71%.

**[flight-time-truth-sql](https://github.com/ShadiShirinbeik/flight-time-truth-sql)**
SQL audit of 1.67M US flight records. At first only 1.75% of reported flight durations matched a recalculation; after fixing time formats, time zones and post-midnight landings, 93.66% did.

**[logistics-sla-tracker](https://github.com/ShadiShirinbeik/logistics-sla-tracker)**
Delivery-time analysis by shipping mode, with nine charts.

### Tools
Python (pandas, seaborn, plotly) · SQL · PostgreSQL · dbt · Tableau · JavaScript · Make · Google Apps Script · OAuth2 · GitHub Actions · Claude Code · Gemini

### Contact
[LinkedIn](https://www.linkedin.com/in/shadishirinbeik/) · shadi.shirinbeik@gmail.com

