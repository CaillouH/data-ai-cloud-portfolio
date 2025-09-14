# Project 1 – Customer Churn & Retention Analytics

**Goal:** Predict customer churn and deliver retention insights.

## 🛠️ Tech Stack
- **Local MVP:** Python (pandas, scikit-learn, XGBoost), DuckDB, Streamlit
- **Optional (cloud):** Azure Data Factory, Snowflake, Power BI, MongoDB

## 📊 Dataset
- Telco Customer Churn (Kaggle) — file: `WA_Fn-UseC_-Telco-Customer-Churn.csv`

## 🚀 How to Run (Local MVP)
```bash
source ~/.venvs/data-portfolio/bin/activate
pip install -r ../../requirements.txt
python train_churn.py
streamlit run app.py


### Project 2 README
```bash
cat > Project2_PaymentAnomaly/README.md << 'EOF'
# Project 2 – Payment Transaction Anomaly Detection (Real-Time)

**Goal:** Detect anomalies/fraud in payment transactions.

## 🛠️ Tech Stack
- **Local MVP (batch):** Python (pandas, scikit-learn RandomForest)
- **Local streaming:** PySpark (local) + Redpanda (Kafka-compatible) or PySpark file stream
- **Optional (cloud):** Databricks (Delta Lake), Kafka/Confluent, Power BI

## 🚀 How to Run (Local MVP)
```bash
source ~/.venvs/data-portfolio/bin/activate
pip install -r ../../requirements.txt
python anomaly_batch.py


### Project 3 README
```bash
cat > Project3_PeopleAnalytics/README.md << 'EOF'
# Project 3 – Employee Productivity & People Analytics

**Goal:** Provide HR & managers insights into workforce productivity and utilization.

## 🛠️ Tech Stack
- **Local MVP:** Python (pandas), DuckDB, Streamlit (synthetic HR/Jira/Slack)
- **Optional (cloud):** ADF, Databricks, Snowflake, Power BI

## 🚀 How to Run (Local MVP)
```bash
source ~/.venvs/data-portfolio/bin/activate
pip install -r ../../requirements.txt
python build_people.py
streamlit run app.py


### Add requirements.txt (if not yet)
```bash
cat > requirements.txt << 'EOF'
duckdb
pyarrow
pandas
scikit-learn
xgboost
streamlit
matplotlib
pyspark
