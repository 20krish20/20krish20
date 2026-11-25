


<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:A1C4FD,100:C2E9FB&height=180&section=header&text=Krishnendra%20Tomar&fontSize=52&fontColor=1E3A8A&animation=fadeIn&fontAlignY=36&desc=Data%20and%20Analytics%20Engineer&descSize=16&descAlignY=56" width="100%" alt="Krishnendra Tomar" />
</p>
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=3EAAFF&center=true&vCenter=true&random=false&width=800&lines=Data+%26+Analytics+Engineer+%40+Pictory+%7C+Ex-Citi;Data+analysis+%E2%80%A2+Data+engineering+%E2%80%A2+AI;Showing+the+business+what+it+couldn't+see+before;MS+Data+Science+%40+UMD+(2026)" alt="Typing SVG" />
  </a>
</p>
<p align="center">
  <a href="https://www.linkedin.com/in/krishnendrasinghtomar/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;
  <a href="mailto:tomarkrishnendra0@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>
<hr />
 
### About Me
 
I turn messy data into numbers a business can trust, and build the pipelines and AI behind them.
 
- **Now:** Data & Analytics Engineer (AI) at **Pictory** (AI video SaaS, internship). I built the customer-segmentation system as the sole engineer, working with the CEO and CTO. It showed leadership how education customers use the product, which the onboarding survey could not, and it now feeds the company's weekly revenue reports.
- **Before:** About 4 years in data roles at **Citi** (payments platform for corporate clients), **TCS / Maersk** and **Six Red Marbles**. At Citi I was lead developer on the Spark pipelines behind a daily risk report and monthly merchant statements, covering ~2 TB of payment data, and fixed a reconciliation report that had been out of balance for six months.
- **Education:** M.S. in Data Science, University of Maryland, College Park (2026), GPA 3.73.
---
 
### Tech Stack
 
<table>
  <tr>
    <td><b>Used at work</b></td>
    <td>
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/Scala-DC322F?style=flat-square&logo=scala&logoColor=white" />
      <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
      <img src="https://img.shields.io/badge/Hive-FDEE21?style=flat-square&logo=apachehive&logoColor=black" />
      <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
      <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" />
      <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
      <img src="https://img.shields.io/badge/AWS_EMR-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
      <img src="https://img.shields.io/badge/Amazon_Bedrock-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>Used in projects</b></td>
    <td>
      <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
      <img src="https://img.shields.io/badge/Delta_Lake-003366?style=flat-square&logo=delta&logoColor=white" />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
      <img src="https://img.shields.io/badge/Anthropic_Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" />
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
      <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
    </td>
  </tr>
</table>
---
 
### Featured Projects
 
#### 🔎 Hybrid RAG Question-Answering System
[View repo](https://github.com/20krish20/Hybrid-RAG-Movie-Q-A-System)
 
Answers two kinds of questions with two engines: semantic search for "find something like this," and LLM-generated pandas code for "compute this." Generated code runs behind a validation layer before it touches the data. Cleaning the embedded text raised recall@10 from 40% to 52%.
 
`FAISS` `sentence-transformers` `pandas` `Python`
 
#### ⚡ Real-Time Payment Reconciliation
[View repo](https://github.com/20krish20/Real-Time-Payment-Reconciliation-Anomaly-Detection-Platform)
 
Matches two payment streams in near real time and flags mismatches, using Spark Structured Streaming and Delta Lake MERGE so reruns never double-count. Inspired by my reconciliation work at Citi.
 
`Kafka` `Spark Streaming` `Delta Lake` `Databricks` `Great Expectations`
 
#### 🤖 Systematic Compliance Agent
[View repo](https://github.com/20krish20/Systematic-Compliance-Agent)
 
An 8-agent pipeline that turns a raw consumer-finance complaint (CFPB data) into a resolution draft citing the right regulation, with a full decision trail.
 
- **Safety first:** PII masking, a review loop that sends weak drafts back (max 2 tries), and human escalation when the model isn't confident.
- **Fairness audit** on every decision.
`LangGraph` `Claude` `DistilBERT` `ChromaDB` `FastAPI` `PostgreSQL` `Docker`
 
> 📌 *All repositories → [github.com/20krish20](https://github.com/20krish20?tab=repositories)*
 
---
 
### Certifications & Awards
 
- AWS Certified Data Engineer - Associate
- AWS Certified Cloud Practitioner
- Google Developers Group (GDG) Hackathon - 2nd prize, Productivity and Automation
---
 
<p align="center">
  <i>Open to Data & Analytics, Data Engineer and AI/ML roles</i>
</p>
 
