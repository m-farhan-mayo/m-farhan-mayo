<!-- HEADER SECTION -->
<div align="center">
  <!-- Dynamic Gradient Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0089D6,232F3E,29B5E8&height=200&section=header&text=Muhammad%20Farhan&fontSize=50&fontAlignY=38&desc=Data%20Engineer%20|%20Cloud%20Architect&descAlignY=60&descAlign=62" alt="Project Banner" />

  <h3 align="center">Building Scalable, Real-Time Data Pipelines & Cloud-Native Architectures</h3>

  <!-- Tech Stack Badges with Perfected Brand Colors -->
  <div align="center">
    <img src="https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure" />
    <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS" />
    <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks" />
    <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white" alt="Spark" />
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
    <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" alt="Snowflake" />
  </div>
  
  <p align="center">
    <br />
    <a href="#-technical-skills"><b>Skills</b></a>
    ·
    <a href="#-featured-engineering-projects"><b>Projects</b></a>
    ·
    <a href="#-contact--connect"><b>Contact</b></a>
  </p>
</div>

---

## 📖 Professional Summary
Data Engineer specializing in building scalable, real-time data pipelines and cloud-native architectures. Expert in **Azure, Microsoft Fabric, Databricks, and dbt**, with a proven track record of developing metadata-driven frameworks and containerized ELT workflows. Skilled in transforming complex datasets into actionable insights through Medallion architectures and automated orchestration.

---

## 🛠️ Technical Skills

| Category | Technologies |
| :--- | :--- |
| ☁️ **Cloud Platforms** | Azure (Databricks, Fabric, Event Hubs, ADF, ADLS Gen2, Synapse), AWS (S3, Glue, Athena, Lambda, IAM) |
| ⚙️ **Data Engineering** | Apache Airflow, dbt, Apache Spark (PySpark), Medallion Architecture, Delta Lake, Kafka |
| 🗄️ **Databases** | Snowflake, Databricks Lakehouse, PostgreSQL, Azure SQL |
| 🚀 **Languages & DevOps** | Python, SQL, Scala, Docker, uv, Git, CI/CD (GitHub Actions) |
| 🧠 **AI & Vector** | LangChain, LangGraph, FAISS, Sentence-Transformers, RAG Pipelines, Semantic Search |

---

## 🏗️ Featured Engineering Projects

<details open>
  <summary><b>🚕 Uber Real-Time Data Engineering (Azure & Databricks)</b></summary>
  <br/>
  <blockquote>
    <b>🎯 The Challenge:</b> Engineering a high-throughput, low-latency streaming architecture to handle concurrent ride-sharing events while ensuring data integrity across a Medallion architecture.
  </blockquote>
  <ul>
    <li>🔵 <b>Data & Scale:</b> Real-time GPS and transaction streams ingested via FastAPI and Azure Event Hubs, processed dynamically into Delta Tables.</li>
    <li>🟢 <b>Implementation:</b>
      <ul>
        <li>Designed a streaming ETL pipeline in Azure Databricks utilizing <b>Spark Structured Streaming</b>.</li>
        <li>Implemented a strict <b>Medallion Architecture (Bronze, Silver, Gold)</b> to provide clean, aggregated datasets for downstream analytics.</li>
        <li>Utilized <b>Azure Schema Registry</b> to manage schema evolution across the event-driven ecosystem, preventing pipeline breakages.</li>
      </ul>
    </li>
  </ul>
</details>

<details>
  <summary><b>🧠 RAG Data Engineering Pipeline | LangChain & Vector Search</b></summary>
  <br/>
  <blockquote>
    <b>🎯 The Challenge:</b> Building a custom Retrieval-Augmented Generation (RAG) system from scratch to overcome the "hallucination" limitations of standard LLMs by bridging unstructured text data with a searchable vector space.
  </blockquote>
  <ul>
    <li>🔵 <b>Data & Scale:</b> Managed unstructured text datasets processed into 384-dimensional vector embeddings using the <code>all-MiniLM-L6-v2</code> model. Built for horizontal scaling via Docker and FAISS.</li>
    <li>🟢 <b>Implementation:</b>
      <ul>
        <li><b>Modular Pipeline Design:</b> Engineered a decoupled Python architecture comprising dedicated modules for ingestion, chunking, embedding, and retrieval to ensure maintainability.</li>
        <li><b>Vector Orchestration:</b> Integrated <b>FAISS</b> for high-speed similarity search and <b>LangChain/LangGraph</b> to orchestrate the "Chain of Thought" prompting.</li>
        <li><b>Automated Workflow & DevOps:</b> Developed an <b>Apache Airflow DAG</b> to automate the raw text-to-index lifecycle. Utilized <b>uv</b> for lightning-fast dependency management and <b>Docker</b> for containerization.</li>
      </ul>
    </li>
  </ul>
</details>

<details>
  <summary><b>🛒 ShoppingMart Data Warehouse (Microsoft Fabric)</b></summary>
  <br/>
  <blockquote>
    <b>🎯 The Challenge:</b> Migrating traditional retail ETL processes to a modern SaaS data lakehouse environment to simplify management and scale-out performance.
  </blockquote>
  <ul>
    <li>🔵 <b>Data & Scale:</b> Multi-source retail transaction data ingested into OneLake using Fabric Notebooks and Data Factory.</li>
    <li>🟢 <b>Implementation:</b>
      <ul>
        <li>Built a unified data repository in <b>Microsoft Fabric Lakehouse</b>, utilizing <b>Delta Tables</b> for strict ACID compliance.</li>
        <li>Orchestrated data flows using <b>Fabric Data Pipelines</b>, automating movement from ingestion to curated Gold layers.</li>
        <li>Utilized <b>SQL Analytics Endpoints</b> within Fabric to enable direct <b>Power BI</b> connectivity for real-time sales reporting.</li>
      </ul>
    </li>
  </ul>
</details>

<details>
  <summary><b>⚙️ Airflow Config-Driven Pipelines (Orchestration Scalability)</b></summary>
  <br/>
  <blockquote>
    <b>🎯 The Challenge:</b> Overcoming "DAG sprawl" by developing a system to programmatically generate Airflow workflows based on central configuration files.
  </blockquote>
  <ul>
    <li>🔵 <b>Data & Scale:</b> Enterprise-grade orchestration capable of scaling across hundreds of independent data tasks without manual hard-coding.</li>
    <li>🟢 <b>Implementation:</b>
      <ul>
        <li>Built a dynamic DAG generator in <b>Apache Airflow</b> that maps YAML metadata definitions to executable workflow patterns.</li>
        <li>Integrated <b>CI/CD pipelines (GitHub Actions)</b> to automatically validate and deploy configuration changes.</li>
        <li>Standardized error handling and alerting mechanisms across the entire pipeline ecosystem using modular Python frameworks.</li>
      </ul>
    </li>
  </ul>
</details>

<details>
  <summary><b>☁️ Cloud-Optima AI-Ops Framework</b></summary>
  <br/>
  <blockquote>
    <b>🎯 The Challenge:</b> Solving the growing complexity and rising costs associated with manual cloud infrastructure scaling across multi-cloud environments.
  </blockquote>
  <ul>
    <li>🔵 <b>Data & Scale:</b> Real-time monitoring telemetry capturing compute spikes and idle times across AWS and Azure instances.</li>
    <li>🟢 <b>Implementation:</b>
      <ul>
        <li>Developed a 3-tier architecture (Monitoring, Intelligence, Execution) utilizing a <b>Reinforcement Learning (Q-Learning)</b> agent.</li>
        <li>Automated predictive cloud resource scaling on <b>AWS and Azure</b>, dramatically reducing idle infrastructure costs while maintaining performance during traffic spikes.</li>
      </ul>
    </li>
  </ul>
</details>

<details>
  <summary><b>🚙 Car Sales Data Warehouse (AWS Native Stack)</b></summary>
  <br/>
  <blockquote>
    <b>🎯 The Challenge:</b> Building a cost-effective, serverless data warehousing solution to handle high volumes of semi-structured automotive sales data for executive BI consumption.
  </blockquote>
  <ul>
    <li>🔵 <b>Data & Scale:</b> Massive-scale automotive sales records, inventory logs, and customer interaction data stored as raw files in Amazon S3.</li>
    <li>🟢 <b>Implementation:</b>
      <ul>
        <li>Architected a serverless ETL pipeline utilizing <b>AWS Glue</b> for heavy data processing and <b>AWS Lambda</b> for event-driven orchestration.</li>
        <li>Implemented a Medallion Architecture to incrementally clean, validate, and enrich data stored in <b>Amazon S3</b>.</li>
        <li>Designed and executed a <b>Star Schema</b> dimensional model to build final Gold tables queried via <b>Amazon Athena</b>.</li>
      </ul>
    </li>
  </ul>
</details>

<details>
  <summary><b>🌍 Parameterized Earthquake API Data Lake</b></summary>
  <br/>
  <blockquote>
    <b>🎯 The Challenge:</b> Fetching and transforming highly nested, unpredictable JSON API data without relying on rigid, pre-built ingestion GUI tools.
  </blockquote>
  <ul>
    <li>🔵 <b>Data & Scale:</b> Continuous ingestion of live global seismic event data via REST APIs.</li>
    <li>🟢 <b>Implementation:</b>
      <ul>
        <li>Built a custom, fully parameterized ingestion engine using <b>pure Python code</b> to programmatically fetch data.</li>
        <li>Pushed raw payload data into a Bronze layer and transformed it into a clean, analytical Silver layer utilizing <b>Azure Databricks</b> and ADLS Gen2.</li>
      </ul>
    </li>
  </ul>
</details>

---

## 🎓 Education & Certifications
* 🎓 **Bachelor of Computer Science** | Superior University, Lahore, Pakistan
* 📜 **Azure Databricks & Spark for Data Engineer** | Udemy
* 📜 **PySpark - Apache Spark Programming** | Udemy

---

## 📩 Contact & Connect
<div align="left">
  <a href="mailto:farhanshoukatali37@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/muhammad-farhan">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="tel:03267789099">
    <img src="https://img.shields.io/badge/Phone-0326--7789099-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Phone" />
  </a>
</div>

---
<div align="center">
  <i>“Data is the new oil, but it's only valuable when it's refined.”</i>
</div>
