# 🌍 ReliefWeb Jobs Dashboard

![Project Status](https://img.shields.io/badge/Production-green)
![Tech Stack](https://img.shields.io/badge/Stack-Nuxt%203%20%7C%20n8n%20%7C%20TailwindCSS-00DC82)

A real-time Business Intelligence (BI) dashboard designed for humanitarian workers to visualize, search, and analyze job opportunities from [ReliefWeb](https://reliefweb.int/).

## 🔗 Demo & Resources

- **Live Demo:** [baena.ai/demos/reliefjobs-dashboard](https://baena.ai/demos/reliefjobs-dashboard)
- **Project Brief:** [baena.ai/projects/reliefweb-jobs-dashboard](https://baena.ai/projects/reliefweb-jobs-dashboard)
- **Explanatory Article:** [baena.ai/articles/jobs-relief](https://baena.ai/articles/jobs-relief)

## 📖 Description

**2025-dashboard-reliefweb-jobs** is an Information Management (IM) tool that aggregates job data specifically for the humanitarian sector. It utilizes the [ReliefWeb API](https://apidoc.reliefweb.int) to update job listings multiple times a day, providing a comprehensive view of opportunities from **July 2025** to the present.

The system is built on a self-hosted instance of [Metabase](https://www.metabase.com/), a powerful open-source Business Intelligence platform.

> **Note:** While the Metabase dashboard layout export is not included (due to subscription limitations), this repository contains all the **n8n workflows** and **data queries** used to build the pipeline.

## ✨ Key Features

* **Live Job Feed:** Automatically fetches the latest humanitarian job postings.
* **Advanced Filtering:** Filter by **Country**, **Organization**, or **Job Type**.
* **Data Visualization:** Charts and metrics on job trends in the sector.
* **Responsive Design:** Optimized for seamless use on desktop and mobile.

## 🛠️ Tech Stack

* **Frontend:** [Nuxt 4](https://nuxt.com/) (Vue.js)
* **Styling:** Tailwind CSS
* **BI Platform:** [Metabase](https://www.metabase.com/)
* **Data Pipeline:** [n8n](https://n8n.io/) (Orchestrating API calls and transformation)
* **Database:** PostgreSQL 16
* **Design:** Figma

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

-----

*Created by Jesus Baena - Focusing on Humanitarian Data Analysis & Information Management.*
