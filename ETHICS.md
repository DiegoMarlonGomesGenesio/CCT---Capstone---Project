# Ethical and Legal Considerations

## Project Overview
This project uses historical electricity consumption and weather data from Tetouan, Morocco, to investigate short-term electricity demand forecasting for operational planning.

## Data Source and Licensing
The project uses the publicly available Power Consumption of Tetouan City dataset from the UCI Machine Learning Repository.

Source: https://archive.ics.uci.edu/dataset/849/power+consumption+

The dataset is distributed under the Creative Commons Attribution 4.0 International (CC BY 4.0) licence. The original source will be acknowledged in the final report and project documentation.

## Privacy and GDPR
The dataset contains electricity consumption measurements for three distribution zones and weather-related variables. It does not appear to contain names, addresses or individual customer identifiers.

The project will not attempt to identify individuals or combine the data with personal records. If any personal data are identified during further inspection, their use will be reassessed in line with applicable data protection requirements.

## Data Security and Integrity
Data will be obtained from the documented public source and stored securely. Original data will be preserved separately from cleaned and processed versions. Data preparation steps and assumptions will be documented to support reproducibility.

## Responsible Modelling
Forecasting models will be evaluated using appropriate error metrics, including Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). A chronological train-test split will be used to avoid training models on future observations.

Only information available at the time of prediction will be used. This is important to prevent data leakage and misleading model performance.

## Limitations and Transparency
The dataset represents electricity consumption in Tetouan during 2017. Findings may not generalise to other cities, electricity networks or periods without additional validation.

Forecasts will be presented as estimates rather than guaranteed outcomes. Model assumptions, limitations and evaluation results will be reported transparently.

## Ethical Use of Results
The project is intended for academic research and demonstration of decision support. It will not directly control electricity infrastructure or make automated operational decisions. Any real-world application would require additional testing, oversight and validation.

## Academic Integrity and AI Use
All external sources will be cited appropriately. Any use of generative AI to support planning, drafting or reviewing project materials will be disclosed in the separate AI-use declaration required for the assessment. The student remains responsible for reviewing and understanding the submitted work.

## EU Artificial Intelligence Act (EU AI Act)

The project will use machine learning to investigate short-term electricity demand forecasting. The EU AI Act will be considered when assessing transparency, reliability, human oversight and potential risks. This academic prototype is not intended for deployment in critical infrastructure. Any future operational deployment would require a separate assessment of the applicable regulatory obligations, including whether the system qualifies as high-risk AI.

## Digital Services Act (DSA)

The Digital Services Act primarily regulates certain online intermediary services and platforms. As this project focuses on analysing a public electricity consumption dataset and developing an academic forecasting prototype, the DSA is not expected to apply directly. Its relevance will be reconsidered if the project's scope changes to include a regulated online service.
