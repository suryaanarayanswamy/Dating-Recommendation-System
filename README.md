# A Trust-Based Dating Network Using Friends-of-Friends-of-Friends (FoFoF) Recommendation  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GG4YPwE189M9sYdN8U3x2Tclk36hvQ4O)  

## Overview  
A graph-based **dating recommendation system** that suggests users exactly **three hops away** in a social network (FoFoF) with **no mutual friends**.  
Filtered candidates using **location overlap** and evaluated **GCN vs GAE** for link prediction on the **Brightkite dataset**.  

- **ROC-AUC:** 0.88 (GAE)  
- **F1 Score:** 0.78 (GAE)  

---

## Tech Stack  
Python · PyTorch · NetworkX · Matplotlib · Scikit-learn  

---

## Dataset  
- Brightkite Social Network: 58K users, 214K friendships, 4.5M check-ins  
- Preprocessed for graph construction + location similarity filtering  
- Source: [Stanford SNAP](https://snap.stanford.edu/data/loc-Brightkite.html)  

---

## More Details  
- 📓 [Colab Notebook](https://colab.research.google.com/drive/1GG4YPwE189M9sYdN8U3x2Tclk36hvQ4O)  
- 📄 [Full Report (PDF)](./annotated-916616559_A%20Trust-Based%20Dating%20Network%20Using%20Friends-of-Friends-of-Friends%28FoFoF%29%20Recommendation.pdf)  
