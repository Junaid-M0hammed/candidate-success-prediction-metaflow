# Metaflow Talent Analytics

**Predict candidate success using Metaflow: from data ingestion to model deployment.**

This project demonstrates how to use Netflix’s [Metaflow](https://github.com/Netflix/metaflow) to build a reproducible, end-to-end machine learning pipeline that predicts the likelihood of a candidate accepting an offer and succeeding post-hire a common challenge in talent acquisition analytics.

> Built with: Python, Metaflow, Pandas, Scikit-learn, SHAP, SQL


## Project Overview

🎯 **Goal:** Forecast candidate success and improve hiring funnel insights using ML.  
🔁 **Pipeline:** Ingest → Clean → Train → Evaluate → Deploy  
⚙️ **MLOps:** Powered by Metaflow for orchestration, experiment tracking, and reproducibility.


## Key Features

- ✅ End-to-end ML pipeline with Metaflow
- 📊 SHAP-based model explainability
- 🔍 Talent-funnel optimization logic
- 📦 Modular structure for reuse
- 🌐 REST API stub for candidate scoring (Flask-ready)

## From prototype to production (and back)

Metaflow provides a simple and friendly pythonic [API](https://docs.metaflow.org) that covers foundational needs of AI and ML systems:
<img src="./docs/prototype-to-prod.png" width="800px">

1. [Rapid local prototyping](https://docs.metaflow.org/metaflow/basics), [support for notebooks](https://docs.metaflow.org/metaflow/managing-flows/notebook-runs), and built-in support for [experiment tracking, versioning](https://docs.metaflow.org/metaflow/client) and [visualization](https://docs.metaflow.org/metaflow/visualizing-results).
2. [Effortlessly scale horizontally and vertically in your cloud](https://docs.metaflow.org/scaling/remote-tasks/introduction), utilizing both CPUs and GPUs, with [fast data access](https://docs.metaflow.org/scaling/data) for running [massive embarrassingly parallel](https://docs.metaflow.org/metaflow/basics#foreach) as well as [gang-scheduled](https://docs.metaflow.org/scaling/remote-tasks/distributed-computing) compute workloads [reliably](https://docs.metaflow.org/scaling/failures) and [efficiently](https://docs.metaflow.org/scaling/checkpoint/introduction).
3. [Easily manage dependencies](https://docs.metaflow.org/scaling/dependencies) and [deploy with one-click](https://docs.metaflow.org/production/introduction) to highly available production orchestrators with built in support for [reactive orchestration](https://docs.metaflow.org/production/event-triggering).



## Getting started

Getting up and running is easy. If you don't know where to start, [Metaflow sandbox](https://outerbounds.com/sandbox) will have you running and exploring in seconds.

### Installing Metaflow

To install Metaflow in your Python environment from [PyPI](https://pypi.org/project/metaflow/):

```sh
pip install metaflow
```
Alternatively, using [conda-forge](https://anaconda.org/conda-forge/metaflow):

```sh
conda install -c conda-forge metaflow
```

Once installed, a great way to get started is by following our [tutorial](https://docs.metaflow.org/getting-started/tutorials). It walks you through creating and running your first Metaflow flow step by step.  

For more details on Metaflow’s features and best practices, check out:
- [How Metaflow works](https://docs.metaflow.org/metaflow/basics)  
- [Additional resources](https://docs.metaflow.org/introduction/metaflow-resources)  

If you need help, don’t hesitate to reach out on our [Slack community](http://slack.outerbounds.co/)!


### Deploying infrastructure for Metaflow in your cloud
<img src="./docs/multicloud.png" width="800px">


While you can get started with Metaflow easily on your laptop, the main benefits of Metaflow lie in its ability to [scale out to external compute clusters](https://docs.metaflow.org/scaling/remote-tasks/introduction) 
and to [deploy to production-grade workflow orchestrators](https://docs.metaflow.org/production/introduction). To benefit from these features, follow this [guide](https://outerbounds.com/engineering/welcome/) to 
configure Metaflow and the infrastructure behind it appropriately.


## 📈 Model Use Case
This pipeline can help Talent Acquisition teams:

- ✅ Predict candidate offer-to-join probability  
- 📊 Forecast hiring outcomes across sourcing channels  
- 🚨 Flag retention risks using pre-hire signals  
- 🧠 Detect bias or bottlenecks in hiring stages  


## 📘 Dataset
This project uses a **synthetic HR dataset** adapted from public sources such as:

- [Kaggle HR Analytics Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Mock Greenhouse/Lever ATS export formats

> ⚠️ *No real candidate data is used in this demonstration.*


## Credits

- 🧬 Built on [Netflix Metaflow](https://github.com/Netflix/metaflow)  
- 📁 Candidate data logic inspired by open HR analytics projects  
- 👨‍💻 Developed by [Junaid Mohammed](https://www.linkedin.com/in/junaid-mohammed-analytics/)
