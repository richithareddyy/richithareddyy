# Richitha Rekula 👋

Hi, I’m Richitha. I’m studying **Data Science, Analytics and Engineering at Arizona State University**, with graduation expected in May 2027. I build tools for exploring code, working with data, and making sense of model predictions.

Most of my projects sit somewhere between **applied AI, machine learning, and software engineering**. I like working through the details: getting the data into shape, building something usable, and checking where it falls short.

[Portfolio](https://richitharekula.vercel.app) · [LinkedIn](https://www.linkedin.com/in/richitha-rekula) · [Résumé](https://richitharekula.vercel.app/Richitha_Rekula_Resume.pdf)

## 🛠️ Software and applied AI

- **[CodeAtlas](https://github.com/richithareddyy/CodeAtlas)** — A tool I built to trace what a change in a Rust repository might affect. It follows dependencies to code and tests, with links to the source behind each connection. There’s a CLI and a GraphQL/SvelteKit workspace backed by Neo4j, plus optional local-model explanations checked against the graph.
- **[ZoomLens](https://github.com/richithareddyy/ZoomLens)** — A screen-share assistant for Zoom: ask about a slide, follow up on an answer, or turn on screen-change announcements and Color Assist. Built with Node.js, WebSockets, FFmpeg, and a vision-model API. Still a development prototype; the accessibility modes have not yet been evaluated with their intended users.
- **[Reddit Data Pipeline](https://github.com/richithareddyy/reddit-data-pipeline)** — An archive loader focused on what happens when data is messy or a load fails halfway through. Python streams records into PostgreSQL with `COPY`; SQL handles merges, and rejected records keep their reasons. Tests cover reruns and interrupted loads. The benchmark uses generated data with injected defects.

## 📊 Models, experiments, and evaluation

- **[GridCast](https://github.com/richithareddyy/GridCast)** — A study of next-day electricity demand in New England. I compared seasonal baselines, LightGBM, and an LSTM, then looked at where forecasts fail and how well their uncertainty estimates hold up during extreme demand. The [offline rebuild audit](https://github.com/richithareddyy/GridCast/blob/main/reports/reproducibility.json) records byte-for-byte matches for all 109 audited artifacts, including the figures.
- **[CauseWay](https://github.com/richithareddyy/CauseWay)** — I started with a randomized email experiment, then deliberately introduced selection bias to see which methods could recover the experimental result. The comparison covers weighting, matching, regression, AIPW, and DML, including what happens when a confounder is hidden.
- **[Support Ticket Triage](https://github.com/richithareddyy/ticket-triage)** — Predicts a ticket’s priority and resolution time, then shows which inputs influenced the prediction. It combines out-of-fold text scores, XGBoost, and SHAP with a Flask API and Streamlit interface. I used synthetic tickets for training and evaluation, so performance on a real support queue is still an open question.

I’ve also built **[StreamBox](https://github.com/richithareddyy/ott-platform)** for catalog search, video range requests, and concurrent updates, or **[Research Paper Summarizer](https://github.com/richithareddyy/research-paper-summarizer)** for PDF processing, summaries, and paper chat.

## ⚙️ Tools I use

- **Languages:** Python · Rust · SQL · TypeScript · JavaScript
- **ML and analysis:** pandas · scikit-learn · PyTorch · LightGBM · XGBoost · SHAP
- **Applications and data:** Node.js · Flask · Streamlit · SvelteKit · PostgreSQL · Neo4j · Docker

The project READMEs explain how to run things, the decisions I made, and what still needs work. You’ll find smaller experiments and coursework in the [full repository list](https://github.com/richithareddyy?tab=repositories).
