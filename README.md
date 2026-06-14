# SQL DataWarehouse and Analytics Project

Welcome to the SQL DataWarehouse and Analytics Project** repository! 🚀
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.


---

## 🏗️ Data Architecture

The data pipeline for this project follows the Medallion Architecture comprised of Bronze, Silver and Gold Layers.

- **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
- **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
- **Gold Layer**: 

*(Add an architecture diagram image here, e.g. `docs/architecture.png`)*

---

## ⚙️ Tech Stack

- **Languages:** Go, Python
- **Streaming:** Apache Kafka (KRaft mode)
- **Validation:** Pydantic
- **Storage:** PostgreSQL, Parquet
- **Containerization:** Docker, Docker Compose

---

## 📂 Repository Structure

```
streamflow/
│
├── producer/          # Go-based Kafka producer
├── consumer/          # Python Kafka consumer with Pydantic validation
├── docker-compose.yml # KRaft-mode Kafka setup
├── docs/               # Architecture diagrams & notes
└── README.md
```

---

## 🎯 Learning Outcomes

This project was built to gain hands-on experience with:
- Kafka fundamentals (topics, partitions, consumer groups)
- Building a producer in Go
- Stream validation and error handling patterns
- Designing pipelines that serve both OLTP and OLAP use cases

---

## 📬 Contact

**MD Tauhid Alam**
Email: tauhidalam9231@gmail.com
LinkedIn: *(add your link)*
