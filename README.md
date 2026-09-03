<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4A90E2,50:50C878,100:9B59B6&height=200&section=header&text=KRISHNA%20CHAITANYA%20BHUPATHI%20RAJU&fontSize=40&fontColor=fff&animation=fadeIn&fontAlignY=35&desc=Data%20Analyst%20%7C%20Analytics%20Engineer%20%7C%20Clinical%20AI%20Architect&descAlignY=51&descSize=18" width="100%"/>
  
  <br/>
  
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bkrishna-chaitanya/)
  [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:krishna.chaitanya007@outlook.com)
  [![Portfolio](https://img.shields.io/badge/Portfolio-4A90E2?style=for-the-badge&logo=google-chrome&logoColor=white)](https://tide-hf.com/)
  [![Location](https://img.shields.io/badge/Location-NY%2C%20USA-50C878?style=for-the-badge&logo=google-maps&logoColor=white)](#)
  
  <br/>
  
  ### 🎯 Data Analyst | Analytics Engineer | Clinical AI Architect
  
  <p align="center">
    <em>Transforming complex healthcare, financial, and operational data into actionable intelligence through advanced analytics, machine learning, and production-grade data infrastructure</em>
  </p>
  
  <br/>
  
  ![Profile Views](https://komarev.com/ghpvc/?username=bkc021102&color=4A90E2&style=for-the-badge&label=PROFILE+VIEWS)
  
</div>

---

## 📊 **EXECUTIVE SUMMARY**

Data Analyst with **3+ years of enterprise experience** architecting end-to-end analytics solutions across **financial services**, **healthcare**, and **operational domains**. Proven expertise in designing **clinical AI pipelines** (TIDE-HF: 546K+ admissions, 0.78–0.98 AUROC), building **governed data warehouses** (500K+ records, 29% faster availability), and delivering **stakeholder-ready dashboards** (18+ Power BI reports, 30% faster analysis).

**Core Value Proposition:**
- **Clinical Analytics Innovation**: Architected TIDE-HF, a production-grade heart failure prediction system processing 137K clinical visits with multi-label ML achieving research-grade performance
- **Enterprise Data Engineering**: Designed PySpark/Kafka pipelines reducing data quality exceptions by 23% and processing time by 17% across 500K+ financial records
- **Governed Analytics Infrastructure**: Built dbt star schemas, DAX measure libraries, and RLS-scoped Power BI solutions translating raw data into executive-ready insights
- **Cross-Functional Leadership**: Partner with 20+ stakeholders across Finance, Ops, and Clinical teams to define KPIs, validate business logic, and deliver scalable analytics

**Technical Differentiators:**
- **Full-Stack Analytics**: SQL → Python → PySpark → dbt → Power BI → Machine Learning
- **Production ML Deployment**: FastAPI + Streamlit + RAG (Mistral 7B + ChromaDB + MCP)
- **Data Governance Expert**: Data quality, validation, lineage, reconciliation, and metric governance
- **Healthcare Domain**: MIMIC-IV clinical datasets, ICD coding, lab analytes, adverse-event prediction

---

## 🗺️ **TECHNICAL ARCHITECTURE & EXPERTISE MAP**

```mermaid
mindmap
  root((KRISHNA CHAITANYA<br/>Data Analyst))
    Data Engineering
      ETL ELT Pipelines
      PySpark Apache Spark
      Apache Kafka Delta Lake
      dbt Data Modeling
      Data Quality Governance
      PostgreSQL Advanced SQL
    Analytics BI
      Power BI Tableau
      DAX Measure Libraries
      Dashboard Design
      KPI Development
      Data Visualization
      Stakeholder Reporting
    Machine Learning
      Scikit learn LightGBM
      XGBoost Random Forest
      Feature Engineering
      Clinical Prediction Models
      Hyperparameter Tuning
      Model Validation
    Cloud Data Platforms
      AWS S3 EC2 Lambda
      Databricks PySpark
      Docker Git GitHub
      Data Warehousing
    Healthcare Analytics
      MIMIC IV Clinical Data
      ICD Coding Lab Analytes
      Adverse Event Prediction
      Clinical Feature Engineering
      Healthcare Data Quality
    Generative AI
      LLM Agents RAG
      OpenAI API Mistral 7B
      ChromaDB MCP
      Prompt Engineering
      FastAPI Streamlit
```

---

## 💼 **CAREER TIMELINE & IMPACT EVOLUTION**

```mermaid
timeline
    title Professional Journey
    section Financial Services
    Jun 2026 : Data Analyst Bristol Myers Squibb
             : 2M+ healthcare records
             : 18+ Power BI dashboards
             : 30% faster analysis
    section Data Engineering
    May 2022 : Data Analyst Hexaware Technologies
             : 500K+ financial records
             : PySpark Kafka pipelines
             : 29% faster data availability
             : 23% fewer quality exceptions
    section Academic Innovation
    Jan 2025 : MS Data Science SUNY Buffalo
             : TIDE HF clinical AI system
             : 546K+ MIMIC IV admissions
             : 0.78 to 0.98 AUROC
             : FastAPI Streamlit deployment
```

---

## 🏗️ **END-TO-END DATA PIPELINE ARCHITECTURE**

<div align="center">

```mermaid
graph TB
    subgraph Sources["📥 DATA SOURCES"]
        A1[POS Systems]
        A2[Shopify/E-commerce]
        A3[EHR/MIMIC-IV]
        A4[Financial Systems]
        A5[Inventory Ledgers]
    end
    
    subgraph Ingestion["🔄 INGESTION LAYER"]
        B1[PySpark ETL]
        B2[Apache Kafka Streams]
        B3[AWS S3 Landing]
        B4[Delta Lake Bronze]
    end
    
    subgraph Transform["⚙️ TRANSFORMATION LAYER"]
        C1[dbt Staging Views]
        C2[Data Quality Checks]
        C3[Feature Engineering]
        C4[dbt Star Schema]
        C5[Dimensional Modeling]
    end
    
    subgraph Warehouse["🗄️ DATA WAREHOUSE"]
        D1[(PostgreSQL)]
        D2[(Delta Lake Silver)]
        D3[Fact Tables]
        D4[Dimension Tables]
        D5[Data Lineage]
    end
    
    subgraph Analytics["📊 ANALYTICS LAYER"]
        E1[Power BI Semantic Model]
        E2[DAX Measure Library]
        E3[Row-Level Security]
        E4[18+ Dashboards]
    end
    
    subgraph ML["🤖 ML PIPELINE"]
        F1[Clinical Feature Eng]
        F2[LightGBM XGBoost]
        F3[Cross-Validation]
        F4[FastAPI Deployment]
        F5[Streamlit UI]
    end
    
    A1 & A2 & A3 & A4 & A5 --> B1 & B2
    B1 & B2 --> B3 --> B4
    B4 --> C1 --> C2 --> C3 --> C4 --> C5
    C5 --> D1 & D2
    D1 & D2 --> D3 & D4 --> D5
    D3 & D4 --> E1 --> E2 --> E3 --> E4
    D3 & D4 --> F1 --> F2 --> F3 --> F4 --> F5
    
    style Sources fill:#4A90E2,stroke:#2E5C8A,stroke-width:2px,color:#fff
    style Ingestion fill:#50C878,stroke:#2E7D4E,stroke-width:2px,color:#fff
    style Transform fill:#9B59B6,stroke:#6A3D7C,stroke-width:2px,color:#fff
    style Warehouse fill:#E67E22,stroke:#A05A1A,stroke-width:2px,color:#fff
    style Analytics fill:#E74C3C,stroke:#A33327,stroke-width:2px,color:#fff
    style ML fill:#F39C12,stroke:#AA6D0C,stroke-width:2px,color:#fff
```

</div>

---

## 🎯 **CLINICAL AI SYSTEM ARCHITECTURE: TIDE-HF**

<div align="center">

```mermaid
graph LR
    subgraph Data["📊 MIMIC-IV Clinical Data"]
        A1[546K+ Admissions]
        A2[60+ ICD Codes]
        A3[70+ Lab Analytes]
        A4[137K Analytical Visits]
    end
    
    subgraph ETL["🔄 Clinical ETL Pipeline"]
        B1[ICD Code Mapping]
        B2[Lab Value Extraction]
        B3[Temporal Alignment]
        B4[Data Quality Validation]
        B5[Feature Engineering]
    end
    
    subgraph Features["⚙️ Feature Engineering"]
        C1[108 Clinical Features]
        C2[Vital Signs]
        C3[Lab Trends]
        C4[Medication History]
        C5[Comorbidity Scores]
    end
    
    subgraph ML["🤖 Multi-Label ML"]
        D1[11 LightGBM Classifiers]
        D2[Cross-Validation]
        D3[Hyperparameter Tuning]
        D4[0.78-0.98 AUROC]
    end
    
    subgraph Deploy["🚀 Production Deployment"]
        E1[FastAPI Backend]
        E2[Streamlit UI]
        E3[RAG: Mistral 7B]
        E4[ChromaDB Vector Store]
        E5[MCP Protocol]
    end
    
    A1 & A2 & A3 --> A4
    A4 --> B1 & B2 & B3
    B1 & B2 & B3 --> B4 --> B5
    B5 --> C1 --> C2 & C3 & C4 & C5
    C2 & C3 & C4 & C5 --> D1 --> D2 --> D3 --> D4
    D4 --> E1 --> E2
    E1 --> E3 --> E4 --> E5
    
    style Data fill:#4A90E2,stroke:#2E5C8A,stroke-width:2px,color:#fff
    style ETL fill:#50C878,stroke:#2E7D4E,stroke-width:2px,color:#fff
    style Features fill:#9B59B6,stroke:#6A3D7C,stroke-width:2px,color:#fff
    style ML fill:#E67E22,stroke:#A05A1A,stroke-width:2px,color:#fff
    style Deploy fill:#E74C3C,stroke:#A33327,stroke-width:2px,color:#fff
```

</div>

---

## 🛠️ **COMPREHENSIVE TECHNOLOGY STACK**

<div align="center">

### **💾 Data Engineering & Warehousing**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD8?style=for-the-badge&logo=databricks&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)

### **📊 Analytics & Business Intelligence**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power_Query-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

### **🤖 Machine Learning & AI**

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge&logo=lightgbm&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB6C3C?style=for-the-badge&logo=xgboost&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

### **☁️ Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![S3](https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white)
![EC2](https://img.shields.io/badge/Amazon_EC2-FF9900?style=for-the-badge&logo=amazon-ec2&logoColor=white)
![Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=aws-lambda&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&