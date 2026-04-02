Overview

StockCausalHeadlines is a Shiny application that estimates the causal effect of news sentiment on stock returns. The project integrates financial data with natural language-derived sentiment features and applies causal inference techniques to estimate treatment effects.

Objectives
	•	Combine financial time series data with news sentiment
	•	Define sentiment-based treatment variables
	•	Estimate causal effects of sentiment on returns
	•	Provide an interactive interface for exploration

Data Sources
	•	Stock price data (Yahoo Finance)
	•	News headlines (NewsAPI or similar sources)

Methodology
	•	Sentiment scoring of headlines
	•	Binary treatment definition (positive vs non-positive sentiment)
	•	Inverse Probability Weighting (IPW)
	•	Causal Forests for heterogeneous treatment effects

Repository Structure
	•	data_pipeline.R: Fetches stock prices and headlines, merges datasets
	•	app.R: Shiny application
	•	data/: Processed datasets

Key Features
	•	Interactive visualization of stock returns
	•	Treatment effect estimation using IPW
	•	Machine learning-based causal effect estimation
	•	Adjustable parameters for analysis

How to Run
	1.	Run data_pipeline.R to generate the dataset
	2.	Launch the Shiny app with app.R

Limitations
	•	Simplified sentiment modeling
	•	Potential confounding in observational data
	•	Limited robustness checks

Future Work
	•	Incorporate transformer-based sentiment models
	•	Add time-series causal models
	•	Improve robustness with sensitivity analysis
	•	Expand to multiple stocks and sectors

Purpose

This project demonstrates the intersection of finance, NLP-derived features, and causal inference in an applied setting.
