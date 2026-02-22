# Noise Impact on Data Visualization and Dimensionality Reduction

## Project Overview

This project investigates how Gaussian noise affects data visualization quality and the performance of dimensionality reduction algorithms.

The study focuses on evaluating the robustness of various visualization techniques when noise is introduced into structured data.
Special attention is given to how well geometric and cluster structures are preserved after dimensionality reduction.

## Objectives

- Analyze the impact of synthetic Gaussian noise on high-dimensional data
- Compare classical visualization techniques and dimensionality reduction methods
- Evaluate structural preservation using quantitative metrics
- Identify which methods are more robust to noisy data

## Key Findings

- Classical (direct) visualization methods remain relatively stable for pre-classified data.
- **PCA** demonstrates strong global stability but loses local structure.
- **t-SNE** preserves local relationships effectively but may generate artificial clusters.
- **UMAP** provides a balanced preservation of both local and global structures.
- Quantitative metrics confirm visual observations.

Noise sensitivity varies significantly across methods, highlighting the importance of selecting appropriate techniques depending on analytical goals.

## Business Relevance

In real-world analytics, dimensionality reduction is widely used for:

- customer segmentation
- anomaly detection
- pattern recognition
- exploratory data analysis

Noisy data can distort cluster separation and decision-making insights.  
This project demonstrates the importance of evaluating robustness before applying visualization and embedding techniques in production environments.
