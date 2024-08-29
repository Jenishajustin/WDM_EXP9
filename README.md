### EX:9 Preprocessing on Twitter Data using Rapidminer

### DATE: 29-08-24

### AIM: 
To implement preprocessing technique on Twitter Data using Rapidminer

### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:
![1](https://github.com/user-attachments/assets/0963bcc9-7a2d-44b0-a5f6-fe52ec1eda9d)
![2](https://github.com/user-attachments/assets/71640a0e-f26f-4084-9ada-24ac01ada49a)
![4](https://github.com/user-attachments/assets/0bba30a6-5460-4308-b9b3-d81177f23fbf)
![3](https://github.com/user-attachments/assets/058f0f0f-334f-464e-9a86-68e89a7138d5)

### Result:
Preprocessing technique on Twitter Data using Rapidminer has been implemented and executed successfully.
