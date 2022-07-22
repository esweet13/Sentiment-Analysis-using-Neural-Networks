# Sentiment-Analysis-using-Neural-Networks

INTRODUCTION

Throughout your career as a data analyst, you will assess continuing data sources for their relevance to specific research questions. Organizations use data sets to analyze their operations. Organizations have many possible uses for these data sets to support their decision-making processes.

In your previous coursework, you have explored a variety of supervised and unsupervised data mining models. You have seen the power of using data analytical techniques to help organizations make data-driven decisions and now want to extend these models into areas of machine learning and artificial intelligence. In this course, you will explore the use of neural networks and natural language processing (NLP).

In this task, you will choose a data file from the Web Links section. The available data sets are as follows: • Amazon Product Data set
• UCSD Recommender Systems Data sets
• UCI Sentiment Labeled Sentences Data set

For this task, you will build a neural network designed to learn word usage and context using NLP techniques. You will provide visualizations and a report, as well as build your network in an interactive development environment.

REQUIREMENTS

Choose one dataset from the Web Links section and use it to complete the following:

Part I: Research Question

A. Describe the purpose of this data analysis by doing the following:
1. Summarize one research question that you will answer using neural network models and NLP
techniques. Be sure the research question is relevant to a real-world organizational situation and
sentiment analysis captured in your chosen dataset.
2. Define the objectives or goals of the data analysis. Be sure the objectives or goals are reasonable
within the scope of the research question and are represented in the available data.
3. Identify a type of neural network capable of performing a text classification task that can be trained to
produce useful predictions on text sequences on the selected data set.

Part II: Data Preparation

B. Summarize the data cleaning process by doing the following:
1. Perform exploratory data analysis on the chosen dataset, and include an explanation of each of the
following elements:
• presence of unusual characters (e.g., emojis, non-Englishcharacters, etc.) 
• vocabulary size
• proposed word embedding length
• statistical justification for the chosen maximum sequence length
2. Describe the goals of the tokenization process, including any code generated and packages that are used to normalize text during the tokenization process.
3. Explain the padding process used to standardize the length of sequences, including the following in your explanation:
• if the padding occurs before or after the text sequence
• a screen shot of a single padded sequence
4. Identify how many categories of sentiment will be used and an activation function for the final dense layer of the network.
5. Explain the steps used to prepare the data for analysis, including the size of the training, validation, and test set split.
6. Provide a copy of the prepared dataset.

Part III: Network Architecture
C. Describe the type of network used by doing the following:
1. Provide the output of the model summary of the function from TensorFlow.
2. Discuss the number of layers, the type of layers, and total number of parameters.
3. Justify the choice of hyperparameters, including the following elements:
• activation functions
• number of nodes per layer
• lossfunction
• optimizer
• stopping criteria 
• evaluation metric

Part IV: Model Evaluation

D. Evaluate the model training process and its relevant outcomes by doing the following:
1. Discuss the impact of using stopping criteria instead of defining the number of epochs, including a
screenshot showing the final training epoch.
2. Provide visualizations of the model’s training process, including a line graph of the loss and chosen
evaluation metric.
3. Assess the fitness of the model and any measures taken to address overfitting. 
4. Discuss the predictive accuracy of the trained network.

Part V: Summary and Recommendations

E. Provide the code used to save the trained network within the neural network.
F. Discuss the functionality of your neural network, including the impact of the network architecture. 
G. Recommend a course of action based on your results.

Part VI: Reporting

H. Create your neural network using an industry-relevant interactive development environment (e.g., an R Markdown document, a Jupyter Notebook, etc.). Include a PDF or HTML document of your executed notebook presentation.

