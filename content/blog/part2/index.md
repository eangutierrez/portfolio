---
title: "Cyclistic Bike-Share Business Case Part Two: Preparation"
description: "Data Analysis Roadmap Step 2: Prepare"
dateString: May 2023
draft: false
tags: ['Data Analysis', 'Data Analytics', 'Data Validation', 'Foldering', 'Organization']
weight: 102
cover:
    image: "images/StockSnap.jpg"
---

# Data Analysis Roadmap Step 2: Prepare

In the Prepare Stage, we must decide what data we need to collect in order to answer all stakeholder questions. We must also decide how to organize the data to maximize its utility. By focusing on what metrics to measure, as well as the security measures to implement, we will successfully complete this stage.

# Cookiecutter Data Science Foldering

Because all the data is provided for us, we should focus on the proper storage and security measures to implement. Using proper foldering techniques is important when working in teams, as this proper organization will minimize lost time. Using the Cookiecutter Data Science template on [Github](https://drivendata.github.io/cookiecutter-data-science/) as a template, I created a Cyclistic\_Bike\_Share project folder with the following folders:

-   **data** (where the project’s data will be stored)  
    \- **external** (data found externally is stored here)  
    \- **interim** (data currently being analyzed is here)  
    \- **processed** (the fully cleaned data is here)  
    \- **raw** (the unprocessed data is here)
-   **docs**
-   **models** (any trained and serialized models are stored here)
-   **notebooks** (any notebook files, such as Jupyter notebooks, are stored here)
-   **references** (any data dictionaries, manual, and explanatory materials are stored here)
-   **reports** (any HTML, PDF, or other generated analysis reports are stored here)  
    \- **figures** (any pgn, jpeg, or other data visualization files are stored here)
- **scripts** (any RStudio scripts are stored here)
- **src** (any source code for this project is stored here)

# Data Changelog File

Another important aspect of the preparation stage is making a Data Changelog file. It is paramount to create and properly use a Data Changelog file, as this file is an explanation of all the notable changes to this data set. This file will be useful for our team to collaborate, keep track of all updates, and ensure all future insights are legitimate.

Before we look at the data, we must establish that the data’s integrity is intact. Only a data set that is reliable, original, comprehensive, current, and cited can be used for analysis, as it helps the client make business decisions based on accurate information. The original, current Cyclistic Bike-Share data was provided by the client, and since we cannot communicate with them to confirm that the data is free from sample biases that do not properly represent the population, human error, and other integral issues, I am making the assumption that the data is fit for analysis. In a real-life scenario, we would hold a meeting with the client to ensure that the data is credible and free of bias. To do so, we would go over the six main areas of data validation

# The Six Pillars of Data Validation

- **Data Type**: ascertain the data matches the data type defined for each field
- **Data Range**: ascertain the data falls within an acceptable range of values defined for each field
- **Data** **Constraints**: ascertain the data meets proper input criteria
- **Data Consistency**: ascertain the data makes sense in the context of other related data
- **Data Structure**: ascertain the data follows a set structure
- **Code Validation**: ascertain the application code systematically performs all validations mentioned above.

# Client Privacy and Data License Agreement

The Cyclistic Bike-Share data is available at: [https://divvy-tripdata.s3.amazonaws.com/index.html](https://divvy-tripdata.s3.amazonaws.com/index.html). To protect the client’s privacy and security, we are saving and encrypting the documents on a password-protected computer. Additionally, we will delete any potential personal identifiable information so that customers are unidentifiable and remain anonymous. Finally, I will adhere to all the terms and conditions granted under this data set’s [Data License Agreement](https://ride.divvybikes.com/data-license-agreement).

# Conclusion

With all of these measures taken, we are ready to move to the third stage of the data analysis process: the Process Stage.

# Reference:

i Google Data Analytics Professional Certificate. (n.d.). _Types of Data Validation_. Coursera. [https://www.coursera.org/learn/analyze-data/supplement/tQAED/types-of-data-validation]

### Image Credits
Image Courtesy of: Ian Livesey