# ELK Stack Mini Project 🚀

## 📌 Overview
This project demonstrates a centralized logging system using the ELK Stack (Elasticsearch, Logstash, Kibana) with Filebeat.

The system collects application logs and visualizes them in Kibana.

---

## 🛠️ Tech Stack
- Docker
- Docker Compose
- Elasticsearch
- Logstash
- Kibana
- Filebeat

---

## 📐 Architecture

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/elk-mini-project.git
cd elk-mini-project
```

### 2. Start the ELK Stack
docker compose up -d

### 3. Generate Logs

```
echo "INFO: Application started" >> logs/app.log
echo "ERROR: Sample error log" >> logs/app.log
```

### 4. Access Kibana

- Open in browser:
```
http://localhost:5601
````

5. Configure Kibana

```
Stack Management → Data Views → Create Data View
```
use:
```
app-logs-*
```

## ✅ Features

Real-time log collection

Centralized log storage

Searchable logs in Kibana

📸 Demo Screenshot

(Add Kibana screenshots here for better portfolio impact)
