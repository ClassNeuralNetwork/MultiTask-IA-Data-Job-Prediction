# AI & DATA JOB PREDICTOR

The goal of this predictor is to assess whether job offers in AI and Data are statistically fair based on the profile and current market.

---

## Project Problem

The global AI and Data market is opaque: professionals in the field clearly know whether a job offer is fair, below, or above market rates, especially when it involves other countries, currencies, and work arrangements. Static sources such as reports and job platforms do not capture the interaction between workload, seniority, location, and work model simultaneously.

---

## Solution

A neural network-based simulator that, given a professional's profile, predicts the offer package the market would have to offer: salary in USD, proportion of remote work, and company location. A senior data scientist in Brazil, for example, could consult the model and receive something like "expect USD 95k, 50% remote, medium-sized company." This information is directly actionable for negotiations and career decisions.

---

## Neural Network Problem

This is a multiple regression problem: the model receives characteristics of the candidate profile and predicts three objectives simultaneously: salary_in_USD, bonus_in_USD, and work mode. Predicting all three at once, besides being laborious, will cause problems due to the different nature of salary regression problems and the multi-class classification of company size and work mode.

---

## Scientific Article

This project was developed with the goal of writing the article "Predição de Vagas de Empregos no Mercado de IA e Dados Utilizando Redes Neurais Artificiais".

Access it at: https://periodicos.ufersa.edu.br/index.php/ecop/article/view/15400

---

### Licensed 

This project is licensed under the ***MIT*** License. You are free to use, copy, modify, and distribute the software, provided you retain the original copyright notices.
