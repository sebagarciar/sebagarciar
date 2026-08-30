# Sebastián García Romero

I ran a $2M/month P&L at Uber Chile before I learned to ship code. Now I do both.

MBA candidate at IE Business School in Madrid, finishing December 2026. Looking for roles in AI product and operations.

I automate the repetitive half of a problem so the half that needs judgment gets more room. Every project below is one attempt at drawing that line.

---

## Projects

### [AI Competitive Intelligence Copilot](https://github.com/sebagarciar/ai-competitive-intelligence)

Watches Chanel, Dior and Gucci across 7 public sources and turns the noise into a weekly strategic brief.

Multi-source ingestion, semantic deduplication, event classification and burst-based trend detection. Every model runs on-device, so a full pipeline run costs $0 in API fees. Includes an evaluation notebook measuring precision and classification F1 against hand-labeled samples.

*Status: pipeline and dashboard run end to end. Built as an applied ML project, not a maintained product. Sample data is checked in, so the dashboard opens with no API keys.*

`Python` `Streamlit` `sentence-transformers` `scikit-learn` `Llama 3.1 via Ollama`

### [Home Finance](https://github.com/sebagarciar/home-finance)

A finance app for a household split between Spain (EUR) and Chile (CLP), holding investments priced in USD. No budgeting app handles three currencies at once, and neither bank offers an API to individuals.

Parses statements from 3 banks, categorizes transactions through a 5-stage cascade that learns from every correction, and runs Monte Carlo retirement forecasts on bootstrapped historical returns rather than a normal-distribution assumption.

*Status: running on my own household finances. 7 of 8 build phases done, debt amortization in progress.*

`FastAPI` `SQLAlchemy` `React` `TypeScript` `NumPy` `Ollama`

---

## Background

**Uber Chile**, Rider Team Lead (2023 to 2025)
Owned the Rider vertical and a $2M+ monthly budget. Grew the user base 16% year over year and took two Chilean cities to #1 market share.

**Chanel**, AI Adoption Strategist (2026)
Built the AI adoption strategy across 7 business functions. Trained 86 employees, rated above 4.7/5. Shipped 10 automations that removed 40+ manual hours per month.

**Simon-Kucher & Partners**, Consultant (2020 to 2022)
Pricing and growth consulting. Built a machine-learning discount tool that cut promotion spend 10% while holding revenue flat. Repriced 15,000+ SKUs for a retail client.

**Education**
Industrial Engineering, Pontificia Universidad Católica de Chile. International MBA, IE Business School.

---

## Contact

Madrid, Spain. EU work permit.

[LinkedIn](https://www.linkedin.com/in/sebastiangarciaromero/)
