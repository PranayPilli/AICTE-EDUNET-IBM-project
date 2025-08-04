# AICTE-EDUNET-IBM-project
# Improved Source of Drinking Water - MIS 78th Round Analysis

## Project Overview

Access to safe and improved sources of drinking water remains a critical issue in India, particularly in rural and socio-economically disadvantaged regions. This project analyzes data from the 78th Round of the Multiple Indicator Survey (MIS) to assess the percentage of the population with access to improved drinking water. It also examines related indicators such as clean cooking fuel usage and migration trends. The study aims to uncover patterns that can inform evidence-based policymaking in alignment with Sustainable Development Goal 6 (SDG 6): Clean Water and Sanitation for All.

## Dataset

- Source: Government of India – AI Kosh  
- Access: [AI Kosh Dataset](https://aikosh.indiaai.gov.in)

## Tools and Technologies

- Platform: IBM watsonx.ai Studio  
- Language: Python  
- Libraries:
  - pandas, numpy – Data handling
  - matplotlib, seaborn – Data visualization
  - scikit-learn – Machine learning modeling
  - ibm_watson_studio_lib – IBM Cloud integration

## Development Approach

1. **Data Collection**  
   Collected survey data from the 78th Round of the Multiple Indicator Survey on water access, cooking fuel usage, and migration.

2. **Preprocessing**  
   Cleaned the dataset, handled missing values, and prepared relevant features for analysis.

3. **Exploratory Data Analysis (EDA)**  
   Created visualizations to understand regional disparities in water access and examine correlations with other indicators.

4. **Modeling**  
   Implemented machine learning models such as Random Forest to predict access patterns to improved water sources.

5. **Deployment**  
   Deployed the trained model as a REST API using IBM watsonx.ai for real-time inference.

6. **Evaluation**  
   Evaluated model performance and validated predictions against actual observations.

## Key Results

- The analysis revealed substantial disparities in water access across regions.
- Areas with lower access to clean cooking fuel also had poor water accessibility.
- Migration trends appeared higher in regions with water infrastructure gaps.
- Insights generated can guide localized and data-driven interventions.

## Sample Outputs

The following are output screenshots from the analysis conducted in IBM watsonx.ai:

### Visualization 1: 

![Screenshot 1](outputs/Screenshot%202025-08-04%20204714.png)

### Visualization 2: 

![Screenshot 2](outputs/Screenshot%202025-08-04%20204759.png)

## Conclusion

This project successfully demonstrates the application of data analytics and machine learning to evaluate critical indicators related to access to clean drinking water. It highlights regional disparities and proposes a scalable approach for decision-making in public policy. The integration with IBM watsonx.ai adds robustness, flexibility, and deployability to the solution.

## Future Enhancements

- Integrate additional data sources such as weather data, IoT sensors, and economic indicators.
- Use advanced ML techniques like deep learning or ensemble methods.
- Expand geographic scope to include more regions and periodic updates.
- Integrate real-time dashboards and policy tools using APIs and cloud services.

## How to Run the Project

1. Clone the repository using:
   ```bash
   git clone https://github.com/PranayPilli/AICTE-EDUNET-IBM-project.git
