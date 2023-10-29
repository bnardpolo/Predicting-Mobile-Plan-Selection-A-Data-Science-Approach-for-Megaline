# Predicting-Mobile-Plan-Selection-A-Data-Science-Approach-for-Megaline
Predicting Mobile Plan Selection: A Data Science Approach for Megaline
# Predicting Mobile Plan Selection: A Data Science Approach for Megaline

## Introduction

The **Predicting Mobile Plan Selection** project focuses on developing a data science model to analyze subscribers' behavior and recommend appropriate plans for a mobile carrier, Megaline. Many of Megaline's subscribers currently use legacy plans, and the company aims to leverage machine learning techniques to encourage their transition to newer plans such as Smart or Ultra.

The project utilizes behavior data obtained from subscribers who have already switched to the new plans, providing valuable insights for the classification task. By building an accurate model, Megaline can effectively predict the suitable plan for each subscriber based on their call frequency, call duration, text message usage, and internet traffic. This personalized approach enables Megaline to optimize its plan recommendations, enhance customer satisfaction, and potentially increase revenue.

## Project Overview

The data preprocessing step has been completed, allowing us to focus directly on creating the model. Through the use of Python and various machine learning libraries, we will split the dataset into training, validation, and test sets. Additionally, we will investigate the performance of different models by adjusting hyperparameters, aiming for the highest possible accuracy.

The project's ultimate goal is to achieve a model accuracy of at least 0.75, as specified by the threshold. This accuracy threshold ensures that the model can reliably recommend the appropriate plan to Megaline subscribers. Furthermore, we will conduct a thorough evaluation of the model's performance using the test dataset to verify its generalizability.

## Model Selection and Results

In this project, we experimented with different models and hyperparameter settings. Here are the key results:

- **Logistic Regression**: Achieved a validation accuracy of 0.7932.
- **Random Forest (Adjusted)**: Achieved a test accuracy of 0.8212, surpassing the performance of the default Random Forest model.
- **Gradient Boosting (Default)**: Achieved a test accuracy of 0.8056.

Based on the results, the **Random Forest (Adjusted)** model outperformed the other models, demonstrating its ability to accurately predict mobile plan selections. The test accuracy exceeded the project's accuracy threshold, indicating its suitability for Megaline's plan recommendations.

## Sanity Check and Further Improvement

A sanity check on the model revealed a validation accuracy of 0.7947. While the model performs reasonably well, there is room for improvement, particularly in reducing the number of incorrect predictions. Analyzing these incorrect predictions can provide valuable insights into areas for further refinement.

## Conclusion

The **Predicting Mobile Plan Selection** project provides Megaline with a robust tool for analyzing subscriber behavior, predicting plan selection, and driving effective decision-making in plan recommendations. By integrating the model into their systems, Megaline can enhance customer satisfaction, optimize plan adoption, and potentially increase revenue.

This project showcases the value of data science and machine learning in providing data-driven insights and driving informed decision-making in the telecommunications industry. With the developed model, Megaline is well-positioned to leverage subscriber behavior data and improve the overall customer experience.

For further details and code, please refer to the project's code repository and documentation.
