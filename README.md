# 🧠 PROCOM - PROJECT COMPLEX - Project Debian

## 📘 Academic Project Notice

This repository contains the information and files of an academic project developed. It was completed as part of a data mining and software analysis course. The work presented here is **for educational and research purposes only**.

---

## 🎯 Project Overview

This project explores the **influence of contributors on the evolution of the Debian project**, with a particular focus on Ubuntu contributors. Ubuntu is a well-known fork of Debian, and this study investigates how the distinct interests and strategic goals of Ubuntu contributors affect their contributions to Debian — and consequently, the development trajectory of the original Debian project.

Using data mining and graph analysis techniques, we seek to understand how:
- **Contribution activity** correlates with project impact
- **Communication patterns** reveal influence and decision-making power
- **Fork dynamics** (specifically Ubuntu → Debian) shape the evolution of open-source infrastructure

---


---

## 🧠 Key Research Question

> **How do contributors — particularly from the Ubuntu project — influence the decisions and evolution of Debian through their contributions, and how do their interests shape the future of the original project?**

This question is explored through descriptive analytics, communication network modeling, and contributor impact metrics.

---

## 📊 Methodology Summary

### ✅ Contribution Analysis

- Number of commits
- Number of files changed
- Timeline of contributions
- Comparative activity patterns between core Debian contributors and Ubuntu-affiliated ones

### 🧩 Communication Graphs

- Using `NetworkX` to build and visualize contributor interaction graphs
- Measuring:
  - Node centrality (influence)
  - Clustering coefficients
  - Connected components (sub-communities)
- Identifying communication bottlenecks and influence zones

---

## 💾 Dataset

The project uses publicly available data on Debian and Ubuntu development activities. This includes (but is not limited to):
- Launchpad contributor metadata
- Mailing lists
- Git commit logs
- Ubuntu/Debian package metadata

For demonstration and prototyping purposes, smaller datasets may have been pre-processed or anonymized.

---

## 🧪 Tools & Technologies

- **Python** (Pandas, NumPy)
- **NetworkX** for graph theory
- **Matplotlib**, **Seaborn** for data visualization
- **Jupyter Notebooks**
- **Git** & **GitHub**

---

## 🔍 What Has Been Done So Far

- Initial data wrangling from Launchpad/git logs
- Extraction of contributor metadata and activity metrics
- Built first version of contributor communication graph
- Identified high-centrality nodes and sub-communities
- Visualized contributions over time

Further analysis will involve:
- Expanding dataset coverage
- Introducing classification models to detect influence
- Exploring contribution causality with respect to package evolution

---

## 📌 Disclaimer

This work is an academic exercise conducted with fellow students. It is not affiliated with or endorsed by the Debian or Ubuntu projects. All analysis and interpretations are intended for learning and research purposes only.
