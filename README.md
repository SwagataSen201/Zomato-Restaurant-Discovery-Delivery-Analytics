# Zomato Restaurant Discovery & Delivery Analytics

An exploratory product analytics project examining restaurant supply, cuisine assortment, rating coverage, affordability, customer engagement, and online delivery availability across Indian cities using a historical Zomato restaurant dataset.

> **Project scope:** This is a descriptive analysis of historical restaurant-level data. It does not represent Zomato's current marketplace performance.

## Repository Structure

- `sql/` — SQL scripts for the eight analytical questions.
- `data/` — Instructions for obtaining and preparing the source dataset.
- `dashboard/` — Power BI dashboard files and screenshots.
- `DATASET_LICENSE.md` — Notes on dataset attribution and licensing.

## Project Overview

Restaurant discovery involves multiple signals, including location, cuisine, price, ratings, customer engagement, and delivery availability.

This project uses SQL (Postgresql) to investigate eight questions about restaurant supply and discovery, compare marketplace characteristics across cities, and identify areas for further investigation.

The objective is to demonstrate how structured data analysis can support product hypotheses and inform subsequent measurement—not to claim unobserved revenue or customer outcomes.

## Business Questions

1. Which Indian cities have the largest restaurant supply?
2. Which cuisine combinations are most common?
3. How does rating coverage vary across cities?
4. How do average restaurant ratings vary across price segments?
5. How does customer engagement vary by rating category?
6. Which restaurants meet the project's value-for-money criteria?
7. How does online-delivery availability vary across cities?
8. Which cities warrant further investigation based on restaurant supply and delivery adoption?


## Data Source and Attribution

**Dataset:** **[Zomato Restaurants Data — Kaggle](https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data)**

**Dataset author:** Shruti Mehta

The dataset is used as the source for this exploratory analysis. Please refer to the original Kaggle dataset page for its applicable licence and terms.

This project is an independent analytical portfolio project and is not affiliated with, sponsored by, or endorsed by Zomato.

## Full Case Study

The complete case study, including all eight analytical questions, SQL findings, product insights, methodology, and limitations, is documented in Notion.

**Case Study:** **[Zomato Product Analytics Case Study](https://app.notion.com/p/Zomato-Restaurant-Discovery-Delivery-Analytics-India-3e55ad086f5880ffac04dc748b5b39b3?source=copy_link)**

The GitHub repository contains the technical implementation and supporting project files. The Notion case study provides the complete analytical narrative.

## Limitations

- The dataset is historical and does not represent Zomato's current marketplace.
- The analysis uses restaurant-level attributes rather than customer-level behaviour.
- The dataset does not contain the orders, revenue, acquisition costs, or retention history needed to calculate conversion, LTV:CAC, churn, or incremental revenue.
- The findings describe patterns and associations; they do not establish causation.
- City comparisons should be interpreted in the context of the dataset and the filters applied.

## Disclaimer

This project is for educational and portfolio demonstration purposes. The analysis and recommendations represent independent work based on a historical third-party dataset. All conclusions are limited to the available data.
