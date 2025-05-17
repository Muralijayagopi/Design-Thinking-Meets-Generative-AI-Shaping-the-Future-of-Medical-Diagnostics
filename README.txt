Project Title: Design Thinking Meets Generative AI: Shaping the Future of Medical Diagnostics

This project integrates Generative AI with Design Thinking principles to create an advanced disease prediction model. Using a dataset of 132 symptoms across 42 disease outcomes, we employed Random Forest classifiers  and HistGradient Boosting to predict diagnoses. This README outlines how Generative AI was utilized throughout each Design Thinking stage—Empathize, Define, Ideate, Prototype, and Test—to enhance the model's accuracy, user-centeredness, and adherence to ethical standards.


-------------------------------------------------------------------

Design Thinking Stages and Generative AI Application

1, Empathize

Objective: 
Understand the needs and expectations of the intended users of this diagnostic tool.

Generative AI Use:

-> Simulating Stakeholder Personas: AI generated realistic personas (e.g., physicians, nurses) based on common roles in healthcare. This allowed us to empathize with typical user workflows, data needs, and concerns, such as interpretability and speed of results.

-> Simulating Patient Scenarios: Generative AI created sample diagnostic scenarios reflecting a range of patient profiles and symptom patterns, giving insights into the diversity of cases healthcare providers face. These insights helped shape the model's requirements.

Outcome: 

We identified the importance of model interpretability and feature transparency for clinical decision support, guiding us toward models like Random Forest and HistGradient Boosting for their interpretability.

-----------------------------------------------------------------------
2, Define

Objective: 
Refine the problem statement to prioritize interpretability, accuracy, and accessibility for healthcare practitioners.

Generative AI Use:

-> Analyzing Stakeholder Feedback: AI clustered feedback from healthcare providers about essential diagnostic features, such as symptom groupings and probability outputs, enabling us to refine our model objectives.

-> Clarifying the Problem Statement: Through feedback analysis, AI helped structure a clear problem statement emphasizing interpretability and ease of use, which are crucial in clinical settings.

Outcome: 

A well-defined problem statement focused on interpretability and accuracy, directly aligning with user needs and shaping the model's development.

-----------------------------------------------------------------------

3, Ideate

Objective: 
Explore innovative solutions and select the best models for disease prediction.

Generative AI Use:
-> Exploring Model Options: AI generated a list of potential models and analyzed their strengths and weaknesses, specifically for interpretability and diagnostic accuracy, highlighting Random Forest and HistGradient Boosting as suitable choices.

-> Feature Engineering Ideas: Generative AI suggested new features, such as interaction terms and symptom clusters, based on observed symptom correlations, inspiring additional features that could improve prediction accuracy.

Outcome: 

Established a rationale for model selection and an initial feature set tailored for healthcare diagnostics.

-----------------------------------------------------------------------

4, Prototype

Objective: 
Develop and refine the diagnostic model prototype to optimize data processing, accuracy, and usability.

Generative AI Use:

-> Data Cleaning and Transformation: AI provided suggestions for data preparation, including steps to handle missing values, resolve inconsistencies, and detect outliers, streamlining data processing.

-> Model Configuration and Tuning: AI suggested hyperparameters to test for HistGradient Boosting and Random Forest, focused on balancing interpretability and performance.

-> Visualization Prototypes: AI generated initial visualizations for disease predictions, feature importance, and probability distributions. Feedback on these visuals from healthcare practitioners informed further improvements.

Outcome: 

A preliminary model optimized for accuracy and aligned with healthcare professionals' need for interpretable, clear outputs.

-----------------------------------------------------------------------

5, Test

Objective: 
Validate the model for accuracy and usability in realistic healthcare settings.

Generative AI Use:

-> Simulating Test Cases: AI generated synthetic test cases representing diverse disease presentations, allowing us to assess the model's robustness and generalization ability.
Automated Performance Evaluation: AI facilitated the automation of testing processes, generating summary statistics on metrics like accuracy, sensitivity, and specificity.

-> Integrating Iterative Feedback: Simulated feedback loops using AI allowed us to anticipate and address common usability and trust concerns, supporting iterative refinement of model explanations and output formats.

Outcome: 

A validated diagnostic model with high accuracy and ease of interpretation, ready for real-world healthcare deployment.

-----------------------------------------------------------------------

6, Ethical Reflection

Throughout the project, ethical considerations were emphasized by incorporating user-centered insights and reducing biases in data and model outputs. Generative AI contributed by identifying potential biases, advising on sensitive data handling, and ensuring compliance with ethical standards in medical AI.

-----------------------------------------------------------------------

7, Conclusion

This README has outlined the integration of Generative AI across the Design Thinking stages, resulting in a diagnostic tool that combines technical precision, interpretability, and practical usability. Generative AI enabled iterative improvements, aligning the final model with healthcare professionals' nuanced requirements. The system offers a responsible, ethical approach to AI in diagnostics, designed to have a real-world impact.