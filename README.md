
Data scientist based in Costa Rica, I build end-to-end data projects from SQL and dashboards to forecasting models and LLM agents that are **evaluated, tested and measured**, not just demoed.

## Featured projects

### AI Engineering

**[Demand Planning Copilot](https://github.com/anCar16/demand-planning-copilot)**: an LLM agent that lets demand planners ask about sales and forecasts in plain language and answers with real numbers from a forecasting system.
- LangGraph agent with tool calling, a read-only SQL guard and provider fallback (Gemini → Groq) with a circuit breaker.
- Evaluated on 33 questions in Spanish and English with answers computed by SQL: **87.9% → 97.0% → 100%** over three iterations, each failure diagnosed and fixed (tool schema, anti-hallucination guard, letting SQL do the arithmetic).
- `Python` `LangGraph` `LiteLLM` `FastAPI` `DuckDB` `pytest` `GitHub Actions`

### Data Science & Machine Learning

**[Retail Demand Forecasting](https://github.com/anCar16/retail-demand-forecasting)**: daily sales forecasts for 1,782 store–product series (Corporación Favorita).
- Time-based backtesting, baselines first, then a global LightGBM model: **RMSLE 0.522 → 0.428 (−18%)**.
- Error analysis by product family and forecast horizon.
- `Python` `LightGBM` `pandas` `Polars`

### Data Analytics & Bi

**[Online Store Database](https://github.com/anCar16/sql-ecommerce-database)**: a MySQL schema with a transactional order procedure (row locking, rollback, error handling) and 13 automated tests in CI.
- `MySQL` `SQL` `GitHub Actions`

**[Power BI Dashboards](https://github.com/anCar16/power-bi-dashboards)**: market share in consumer goods, banking transactions in Costa Rica and world population, with DAX measures and KPI targets.
- `Power BI` `DAX` `Power Query`

## Tech stack

**Languages:** Python, SQL
**Data & ML:** pandas, Polars, scikit-learn, LightGBM, DuckDB
**GenAI:** LangGraph, LiteLLM, tool calling, LLM evaluation
**Engineering:** FastAPI, pytest, uv, Git, GitHub Actions
**BI:** Power BI, DAX

## Contact

<!-- Add your LinkedIn URL below -->
[LinkedIn](https://www.linkedin.com/in/your-profile)
