# 📡 Real Telecom Data Ingestion

> Real-time telecom data ingestion pipeline built using n8n, REST APIs, JavaScript, and workflow automation to collect, validate, normalize, and store telecom network events for AI-powered analytics.

![Status](https://img.shields.io/badge/Project-Completed-success)
![Automation](https://img.shields.io/badge/n8n-orange)
![AI Ready](https://img.shields.io/badge/AI-Ready-blue)
![Telecom](https://img.shields.io/badge/Domain-Telecom-green)

---

# 🚀 Overview

Telecom networks continuously generate operational events from Core Network Functions and Radio Access Networks.

This project demonstrates an automated ingestion pipeline that receives real-time telecom events, validates them, normalizes the data, enriches metadata, and stores them for AI-powered downstream applications.

---

# Features

- Real-time Event Ingestion
- REST API Integration
- Data Validation
- JSON Normalization
- Metadata Enrichment
- Google Sheets Storage
- AI-ready Data Pipeline
- Workflow Automation

---

# Workflow

```
REST API

↓

Receive Telecom Event

↓

Validate Payload

↓

Normalize JSON

↓

Enrich Metadata

↓

Google Sheets Database

↓

Ready for AI Processing
```

---

# Technology Stack

- n8n
- JavaScript
- REST APIs
- Google Sheets
- Webhooks
- JSON Processing
- Telecom Data Models

---

# Supported Network Elements

- AMF
- SMF
- UPF
- UDM
- AUSF
- PCF
- NRF
- gNB

---

# Sample Telecom Event

```json
{
"network_element":"UPF",
"alarm":"PFCP Association Failure",
"location":"Bangalore",
"severity":"Critical"
}
```

---

# Business Benefits

✔ Standardized telecom data

✔ AI-ready datasets

✔ Faster analytics

✔ Simplified integrations

✔ Improved data quality

✔ Real-time processing

---

# Future Roadmap

- Kafka Integration
- MongoDB
- Elasticsearch
- Grafana
- AI Prediction
- Vector Database
- Streaming Analytics

---

# Author

**Niranjan Kumar K**

AI Automation Engineer | Telecom | AIOps
