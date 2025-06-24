Cardiovascular Risk Analysis – AI-Based Expert System

Introduction

With cardiovascular diseases (CVDs) being a leading cause of mortality worldwide, technology-driven solutions hold transformative potential for early detection and treatment. This project documents my journey of building an AI-powered expert system that combines:

H2O’s AutoML for predictive accuracy

Rule-based reasoning (Forward & Backward Chaining) for diagnostic verification

BERT model for personalized treatment recommendations


Project Overview

The primary goal of this project was to develop a reliable AI system capable of early detection of cardiovascular conditions and providing customized treatment guidance. This was achieved by integrating:

Forward and Backward Chaining – For rule-based diagnosis

H2O AutoML – For automated model selection and hyperparameter tuning

BERT – For advanced, context-aware treatment recommendations



Data and Tools Used

The dataset included key cardiovascular health indicators such as blood pressure, cholesterol levels, age, and more.

Technologies and Libraries:

H2O AutoML – Automated machine learning for predictive modeling

Python – For data preprocessing, rule engine logic, and integration

BERT (Transformer model) – For natural language processing and treatment suggestion generation



Key Features of the System

Forward Chaining – Diagnostic Inference
The system begins with user-provided symptoms and applies medical rules to identify possible cardiovascular conditions. This approach incrementally builds a hypothesis, enhancing early detection.

Backward Chaining – Diagnostic Verification
To minimize false positives, the system verifies forward conclusions by tracing back through the rule set to ensure all necessary conditions are met.

H2O AutoML – Predictive Precision
Using AutoML, the system selects and tunes high-performing models based on metrics like accuracy and AUC, predicting the probability of a cardiovascular event.

BERT – Personalized Treatment Recommendations
Following diagnosis, the system uses BERT to recommend evidence-based and context-specific treatment strategies tailored to individual patient profiles.


Challenges and Solutions

Data Quality and Missing Values:
Handling missing values and ensuring data accuracy were critical. Using H2O’s na_omit function allowed me to manage missing data without manual intervention.

Complexity of Backward Chaining in Python:
Implementing backward chaining required careful rule-setting to avoid infinite loops. I addressed this by establishing clear stopping conditions and prioritizing the most critical symptoms.

Integrating BERT Recommendations
Creating a seamless integration between the predictive model and BERT for treatment suggestions was challenging. I resolved this by designing a separate pipeline for BERT post-prediction to avoid interference with the main diagnostic model.

Outcome and Future Enhancements
The system successfully categorizes patient risk levels and provides evidence-based recommendations. Future directions include integrating more data sources, improving the BERT model with more specialized medical data, and adding multi-language support to reach broader audiences.



Conclusion

This project demonstrates the power of combining symbolic AI with machine learning to support critical healthcare applications. While the road to building AI-driven healthcare systems is complex, the impact is immensely rewarding. Continuous improvement and integration of such systems could revolutionize global healthcare accessibility and accuracy.

