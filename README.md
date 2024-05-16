# Abstract

In the wake of the COVID-19 pandemic, understanding and analyzing data related to the spread and impact of the virus have become paramount. This project delves into Pandemic Data Science, focusing on various aspects such as wave-wise trends in cases, growth speeds, Case Fatality Rates, post-vaccination dynamics including the speed of vaccine distribution compared to the spread of cases, effect of beds on deaths etc. Understanding these factors give an idea about the factors which affected the pandemic, and help us be prepared for similar situations in the future.

## Introduction and Problem Definition

The primary objective of this project was to conduct a comprehensive analysis of pandemic-related data to gain insights into the spread and impact of COVID-19 across different dimensions. Specifically, we aim to:

- Analyze wave-wise trends in COVID-19 cases, examining factors such as growth speeds and factors affecting the number of cases.
- Understand the Case Fatality Rate (CFR) relevant to COVID - 19 and exploring the factors responsible for the same.
- Compare the effect of the pandemic in India state-wise with respect to various factors and metrics.

## Some Important Theory

### Case Fatality Rate (CFR)

The Case Fatality Rate (CFR) is a measure used in epidemiology to assess the severity of a disease. It represents the proportion of confirmed cases of a disease that result in death.

### Pearson Correlation Coefficient

The Pearson Correlation Coefficient is a measure of the linear correlation between two variables.

### Population Density

Population density is the number of people per unit area, usually expressed as people per square kilometer or square mile.

### Number of Beds per Thousand

The number of beds per thousand people is a measure of healthcare infrastructure.

### Health Index

The health index is a composite measure that assesses various indicators of health.

### Testing Rate of COVID-19

The testing rate of COVID refers to the number of COVID-19 tests conducted per unit population.

## Techniques and Procedure

### Obtaining and Cleaning the Dataset

We obtained the following datasets: Health Index, Hospital Beds, Statewise Testing Details, COVID-19 India, COVID Vaccine Statewise, and Population Index.

### Calculating Pearson Correlation Coefficient

We calculated the Pearson correlation coefficient between each factor and the Case Fatality Rate (CFR) to identify the variables that significantly differed.

## Experimental Results

Here are the experimental results from the analysis.

### Some Statistical Analysis

- CFR (Case Fatality Rate): The mean CFR across the states is approximately 1.93\%.
- Testing Rate per Thousand: On average, states have conducted about 47.72 tests per thousand people.
- Beds per Thousand: The mean number of hospital beds available per thousand people is about 0.96.

### Analysis of Factors

Pearson Correlation Coefficient with CFR:
- Per Capita Cases: -0.155
- Population Density: -0.087
- Number of Beds: -0.203
- Health Index: -0.071


