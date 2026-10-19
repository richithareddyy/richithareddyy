# Richitha Rekula 👋

I’m an M.S. student in **Data Science, Analytics and Engineering at Arizona State University**, graduating in May 2027. I build tools for working with code, documents, and data, and study how to evaluate the models behind them.

My work spans **Applied AI · ML Engineering · Data Science · Software Engineering**. I’m interested in the whole path from an experiment to an application: how data reaches a model, how its output reaches a user, and what evidence supports the result.

[Portfolio](https://richitharekula.vercel.app) · [LinkedIn](https://www.linkedin.com/in/richitha-rekula) · [Résumé](https://richitharekula.vercel.app/Richitha_Rekula_Resume.pdf)

## 🛠️ Software and applied AI

- **[CodeAtlas](https://github.com/richithareddyy/CodeAtlas)** — What might break when a Rust function changes? Static analysis traces dependencies to affected code and tests, with links back to source lines. Includes a standalone CLI, a Neo4j graph, and a GraphQL/SvelteKit workspace. Optional local-model explanations are checked against graph evidence.
- **[ZoomLens](https://github.com/richithareddyy/ZoomLens)** — A screen-share assistant for Zoom: ask about a slide, follow up on an answer, or turn on screen-change announcements and Color Assist. Built with Node.js, WebSockets, FFmpeg, and a vision-model API. Still a development prototype; the accessibility modes have not yet been evaluated with their intended users.
- **[Reddit Data Pipeline](https://github.com/richithareddyy/reddit-data-pipeline)** — A Python/PostgreSQL archive loader built around streaming `COPY`, set-based merges, and explicit rejection records. Tests cover reruns and interrupted loads; the published benchmark uses generated data with injected defects.

## 📊 Models, experiments, and evaluation

- **[GridCast](https://github.com/richithareddyy/GridCast)** — Next-day electricity-demand forecasting for New England. Compares seasonal baselines, LightGBM, and an LSTM with chronological backtesting, then examines uncertainty and errors during extreme demand. The [offline rebuild audit](https://github.com/richithareddyy/GridCast/blob/main/reports/reproducibility.json) records byte-for-byte matches for all 109 audited artifacts, including the figures.
- **[CauseWay](https://github.com/richithareddyy/CauseWay)** — When does an observational estimate recover an experimental answer? Starts with a randomized email experiment, constructs confounded samples, and compares weighting, matching, regression, AIPW, and DML. The findings show where adjustment works and where hidden confounding defeats it.
- **[Support Ticket Triage](https://github.com/richithareddyy/ticket-triage)** — Priority classification and resolution-time prediction using out-of-fold text scores, XGBoost, and SHAP, served through Flask and Streamlit. Training and evaluation use synthetic tickets; the results are not claims about a real support queue.

For more application work, see **[StreamBox](https://github.com/richithareddyy/ott-platform)** for catalog search, video range requests, and concurrent updates, or **[Research Paper Summarizer](https://github.com/richithareddyy/research-paper-summarizer)** for PDF processing, summaries, and paper chat.

## ⚙️ Tools I use

- **Languages:** Python · Rust · SQL · TypeScript · JavaScript
- **ML and analysis:** pandas · scikit-learn · PyTorch · LightGBM · XGBoost · SHAP
- **Applications and data:** Node.js · Flask · Streamlit · SvelteKit · PostgreSQL · Neo4j · Docker

Each project README covers setup, technical decisions, evaluation, and limitations. Smaller experiments and coursework are in the [full repository list](https://github.com/richithareddyy?tab=repositories).
