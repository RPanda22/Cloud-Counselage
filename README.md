# Cloud-Counselage

## Student Placement and Graduation Year Prediction

This repository contains two machine learning projects aimed at predicting student placement status and forecasting graduation years based on academic data.

## Student Placement Prediction

The Student Placement Prediction project focuses on developing a machine learning model capable of accurately predicting whether students secure placement based on various academic and personal attributes. The model analyzes factors such as academic records, extracurricular activities, and previous placement results to provide actionable insights into placement outcomes.

### Key Features:
Data Collection and Preprocessing:

* The project begins by collecting a diverse range of student data, including academic records, extracurricular activities, and previous placement status.
* Data preprocessing techniques are then employed to clean the dataset, handle missing values, and encode categorical variables.
Model Selection:

* To identify the most suitable predictive model, the project evaluates four state-of-the-art machine learning algorithms: Random Forest, Decision Trees, Logistic Regression, and Support Vector Machines (SVM).
* Each model undergoes rigorous testing and validation to determine its accuracy and performance.

Best Model Selection:
* Following thorough evaluation, the project selects the best-performing model based on key metrics such as accuracy, precision, recall, and F1-score.
* The chosen model demonstrates superior predictive capabilities and is deemed most effective for the task at hand.
  
Model Training and Evaluation:
* The selected model undergoes intensive training using the preprocessed dataset.
* Training is followed by comprehensive evaluation to assess the model's performance on both training and validation datasets.
* Evaluation metrics such as confusion matrix, and precision-recall curve are utilized to gauge the model's effectiveness.
  
Output Handling:
* Upon successful training and evaluation, the model generates predictions for student placement outcomes.
* The predicted placement status for each student is then stored in a separate output file for easy access and analysis.
* This output file provides stakeholders with actionable insights into placement outcomes, enabling informed decision-making.
  
Impact and Benefits:
* The Student Placement Prediction project offers significant benefits to educational institutions, recruiters, and students alike.
* By accurately forecasting placement outcomes, institutions can optimize their career guidance services and enhance student employability.
* Recruiters gain valuable insights into candidate profiles, enabling them to make informed hiring decisions and identify top talent.
* Students benefit from personalized career guidance and increased opportunities for securing desirable placements.

In summary, the Student Placement Prediction project represents a groundbreaking initiative to leverage data-driven insights for enhancing student placement outcomes and fostering career success.

## Graduation Year Forecasting

The Graduation Year Prediction project aims to develop a robust predictive model for forecasting students' graduation years based on academic data. By leveraging historical information and datetime functions, this project seeks to provide educational institutions and students with accurate predictions regarding their time to graduation.

### Key Features:

Data Collection and Preprocessing:

* Diverse student data, including academic records and college details, is collected for analysis.
* Data preprocessing techniques are applied to clean the dataset, handle missing values, and encode categorical variables.

Extraction of Year from Created Column:

* Utilizing datetime functions, the project extracts the year from the 'Created' column in the dataset.
* This extracted year serves as a crucial component in predicting students' graduation years accurately.

Prediction Model Development:

* The project develops a prediction model based on academic year and current date, considering standard course durations.
* Different scenarios are considered, such as 3-year and 4-year course durations, to accommodate varying academic programs.

Contextual Information Generation:

* Predicted graduation years are generated along with contextual information explaining the basis of the prediction.
* Contextual details include the academic year, current year, and standard course duration, providing stakeholders with valuable insights.

Output Handling:

* The predicted graduation years, along with contextual information, are stored in a separate output file for easy reference and analysis.
* Stakeholders can access this output file, "Predicted_Graduation_with_Context.xlsx", to make informed decisions regarding academic planning and career progression.

Impact and Benefits:

* Educational institutions can utilize the predictions to optimize academic planning and student support services.
* Students gain valuable insights into their academic timelines, allowing for better career planning and goal setting.
* The project fosters a data-driven approach to academic guidance, enhancing student success and graduation outcomes.

In conclusion, the Graduation Year Prediction project offers a valuable tool for educational institutions and students to forecast graduation years accurately, thereby facilitating effective academic planning and career development.

Both projects aim to assist educational institutions, recruiters, and students in making informed decisions regarding career opportunities and academic planning.

Navigate to the respective project directories (`Year of Graduation` or `Placement status prediction`) and find the colab files (.ipynb).
All the project deliverables are available directly in the main branch itself.


## Contributor and Author

- [Roshan Panda](https://github.com/RPanda22)



