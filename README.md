# Snowflake Labs 

This repository contains consolidated resources, scripts, and documentation for the Snowflake labs we are working on. The labs focus on **data engineering pipelines, Snowpark, and Snowflake notebooks**, helping us gain hands-on experience with Snowflake's capabilities.

---

##  Labs Overview

### **Lab 1: Data Engineering Pipelines with Snowpark (Python)**
- **Quickstart Guide:** [Data Engineering Pipelines with Snowpark Python](https://quickstarts.snowflake.com/guide/data_engineering_pipelines_with_snowpark_python/index.html?index=..%2F..index#0)
- **GitHub Repo:** [Snowflake Labs Guide](https://github.com/Snowflake-Labs/sfguide-data-engineering-with-snowpark-python?_fsi=1GCzoPPC)
- **YouTube Tutorial:** [Watch Here](https://www.youtube.com/watch?v=yTUneS1WXao)

#### **Description**
This lab explores **Snowpark for Python**, focusing on data engineering pipelines using **Snowflake as a processing engine**. It includes:
- Writing and executing Snowpark Python scripts.
- Working with data frames in Snowpark.
- Running transformations within Snowflake.

---

### **Lab 2: Building Data Engineering Pipelines using Snowpark Notebooks**
- **Hands-On Lab Webinar:** [Register & Attend](https://www.snowflake.com/webinars/virtual-hands-on-labs/build-data-engineering-pipelines-using-snowpark-in-snowflake-notebooks-2025-02-12/)
- **Quickstart Guide:** [Data Engineering with Notebooks](https://quickstarts.snowflake.com/guide/data_engineering_with_notebooks/index.html?index=..%2F..index#0)
- **GitHub Repo:** [`sfguide-data-engineering-with-notebooks-main`](Lab2/sfguide-data-engineering-with-notebooks-main)

#### **Description**
This lab introduces **Snowflake Notebooks** and their integration with Snowpark for building scalable data engineering pipelines. Key topics covered:
- Creating and running Snowflake notebooks.
- Executing Snowpark transformations interactively.
- Integrating data workflows with Snowflake services.

---

### **Lab 3: Getting Started with Native Apps**
- **Quickstart Guide:** [Getting Started with Native Apps](https://quickstarts.snowflake.com/guide/getting_started_with_native_apps/#0)

#### **Description**
This lab covers **native applications** in Snowflake, providing an overview of how to build and deploy **custom Snowflake applications**. Topics include:
- Understanding **Native Apps architecture**.
- Deploying apps within the Snowflake ecosystem.
- Managing app security and data governance.

---

##  Setup & Prerequisites
To follow along with the labs, ensure you have:
- **Snowflake Account** (Trial or Enterprise)
- **Snowflake CLI & SnowSQL Installed**
- **Python 3.8+** (for Snowpark)
- **VS Code / Jupyter Notebook** (for local development)
- **Access to Snowflake Quickstart Guides & Webinars** (links above)

---

##  Repository Structure
```
snowflake-labs-ubm/
│──  Lab1/        # Contains all scripts, notebooks, logs, and results for Lab 1
│──  Lab2/
│   ├──  sfguide-data-engineering-with-notebooks-main/  # Lab 2 Notebooks & Scripts
│   ├── logs/       # Log files from script executions
│   ├── images/     # Screenshots and result images
│   ├── runs/       # Executed run files
│
│──  Lab3/        # Contains scripts, apps, logs, and results for Lab 3
│   ├── streamlit/     # Screenshots and result images│
│── .gitignore      # Ignoring unnecessary files
│── LICENSE         # License for the repository
│── README.md       # This file
```

---

## How to Use This Repository
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-org/snowflake-labs-ubm.git
   cd snowflake-labs-ubm
   ```

2. **Navigate to the Lab Folder**
   ```sh
   cd Lab1
   ```

3. **Run Scripts / Notebooks**
   - Open `.ipynb` notebooks in Jupyter or VS Code.
   - Run Python scripts using:
     ```sh
     python script_name.py
     ```

4. **Check Logs & Runs**
   - Log files from each run are saved in the respective **logs/** folder.
   - Screenshots and results are in **images/**.
   - Executed run files are stored in **runs/**.

---

##  Important Notes
- **All logs, execution details, and results are stored in their respective folders under each lab.**  
---
## Team Members  

- **Sai Priya Veerabomma** - 33.3% (Lab3)  
- **Sai Srunith Silvery** - 33.3% (Lab2)  
- **Vishal Prasanna** - 33.3% (Lab1)  

---


