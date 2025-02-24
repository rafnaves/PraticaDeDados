# Introduction (Data Science)

# Introduction

> Data Analytics is a core component of a Data Analyst’s role. The field involves extracting meaningful insights from raw data to drive decision-making processes. It includes a wide range of techniques and disciplines ranging from the simple data compilation to advanced algorithms and statistical analysis. As a data analyst, you are expected to understand and interpret complex digital data, such as the usage statistics of a website, the sales figures of a company, or client engagement over social media, etc.
> 
- **Descriptive Analytics**

This type of analystic extracts knownledge from past data bases, to understand patterns and draw trends. 

[What is Descriptive Analytics | Data Analytics | Techcanvass (youtube.com)](https://www.youtube.com/watch?v=K1a9oSybtm4)

<img align="center" src="https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/Untitled.png"/>

- **Descriptive Analytics**

Diagnostic analytics, as a crucial type of data analytics, is focused on studying past performance to understand why something happened. Through techniques such as drill-down, data discovery, correlations, and cause-effect analysis, data analysts utilizing diagnostic analytics can look beyond general trends and identify the root cause of changes observed in the data.

- **Predictive Analysis**

 It refers to the practice of extracting information from existing data sets in order to determine patterns and forecast future outcomes and trends. Data analysts apply statistical algorithms, machine learning techniques, and artificial intelligence to the data to anticipate future results.

- **Prescriptive Analytics**

As a data analyst, the goal of prescriptive analytics is to recommend various actions using predictions on the basis of known parameters to help decision makers understand likely outcomes. Prescriptive analytics employs a blend of techniques and tools such as algorithms, machine learning, computational modelling procedures, and decision-tree structures to enable automated decision making. Therefore, prescriptive analytics not only anticipates what will happen and when it will happen, but also explains why it will happen, contributing to the significance of a data analyst’s role in an organization.

## **Key Concepts for Data**

> In the broadest sense, data can be classified into various types like nominal, ordinal, interval and ratio, each with a specific role and analysis technique. Higher-dimensional data types like time-series, panel data, and multi-dimensional arrays are also critical. On the other hand, data quality and data management are key concepts to ensure clean and reliable datasets.
> 
1. Data Mining: Unearthing Hidden Patterns

Data mining is the process of discovering meaningful patterns, relationships, and knowledge from vast amounts of data. Through various techniques, such as clustering, classification, and association, data miners extract valuable information from structured and unstructured data. This concept is instrumental in identifying customer behavior, market trends, and predicting future outcomes.

1. Statistical Analysis: Drawing Inferences from Data

Statistical analysis is a cornerstone of data analytics, providing a framework for drawing inferences and making decisions based on data. By applying statistical methods like hypothesis testing, regression analysis, and ANOVA, analysts can assess data variability, uncover correlations, and validate conclusions. This concept ensures that data-driven insights are accurate, reliable, and meaningful.

### **Data Collection**

> **Data collection** is a systematic process of gathering observations or measurements. Whether you are performing research for business, governmental or academic purposes, data collection allows you to gain first-hand knowledge and original insights into your [research problem](https://www.scribbr.com/research-process/research-problem/).
> 

While for different porpuses and objectives the methods can change, in general they remain the same and you need to consider the

1. **aim of research**
2. **the type of data that we’ll collect**
3. **the methods and procedures we’ll use to collect, store and process the data**

### Aim of research

> what is the practical or scientific issue that you want to address and why does it matter?
> 

Define what kind of data i will collect is also important since it can be:

- [**Quantitative data**](https://www.scribbr.com/methodology/quantitative-research/) is expressed in numbers and graphs and is analyzed through [statistical methods](https://www.scribbr.com/?cat_ID=34372).
- [**Qualitative data**](https://www.scribbr.com/methodology/qualitative-research/) is expressed in words and analyzed through interpretations and categorizations.

### **Data collection method**

<img align="center" src="https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/Untitled%201.png"/>

### **Data collection procedures**

- **Operationalization**

Is the process of transforming abstract concepts indo measurable methodos like, qualitative→quantitative

- **Sampling**

This involves defining a [population](https://www.scribbr.com/methodology/population-vs-sample/), the group you want to draw conclusions about, and a sample, the group you will actually collect data from.

- **data management plan**

basically the creation of a data

### **Cleanup**

> The cleanup of data is the analysis of the data, with the aim of transforming and modelling it to discover usefull information.  For starters, it’s good practice to keep on top of your data, ensuring that it’s accurate and up-to-date. However, data cleaning is also a vital part of the data analytics process. If your data has inconsistencies or errors, you can bet that your results will be flawed, too. And when you’re making business decisions based on those insights, it doesn’t take a genius to figure out what might go wrong!
> 
- **Rogue data:** Rogue data’ includes things like incomplete, inaccurate, irrelevant, corrupt or incorrectly formatted data. The process also involves deduplicating, or ‘deduping’. This effectively means merging or removing identical data points.
    
    Essentially, GIGO means that if the quality of your data is sub-par, then the results of any analysis using those data will also be flawed. Even if you follow every other step of the data analytics process to the letter, if your data is a mess, it won’t make a difference.
    
    For this reason, the importance of properly cleaning data can’t be overstated. It’s like creating a foundation for a building: do it right and you can build something strong and long-lasting. Do it wrong, and your building will soon collapse. This mindset is why good data analysts will spend anywhere from **60-80% of their time** carrying out data cleaning activities. Beyond data analytics, good data hygiene has several other benefits. Let’s look at those now.
    
- **How to clean your data (step-by-step)**
    
    **Step 1: Get rid of unwanted observations: data that doesnt fit the aim of the project**
    
    **Step 2: Fix structural errors: the catalogue of data is very important, thats why a good data base is needed**
    
    **Step 3: Standardize your data: every type of data shoud fit the same stardants, like begging with lower case**
    
    **Step 4: Remove unwanted outliers**
    
    **Step 5: Fix contradictory data errors**
    
    **Step 6: Type conversion and syntax errors**
    
    **Step 7: Deal with missing data**
    
    **Step 8: Validate your dataset**
    

### Exploration

<img align="center" src="https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/Untitled%202.png"/>

> Typically, this exploration process involves discerning patterns, identifying anomalies, examining underlying structures, and testing hypothesism which often gets accomplished via descriptive statistics, visual methods, or sophisticated algorithms.
> 
- **The main purpose of EDA is to help look at data before making any assumptions. It can help identify obvious errors, as well as better understand patterns within the data, detect outliers or anomalous events, find interesting relations among the variables.**

Specific statistical functions and techniques you can perform with EDA tools include:

- Clustering and dimension reduction techniques, which help create graphical displays of high-dimensional data containing many variables.
- Univariate visualization of each field in the raw dataset, with summary statistics.
- Bivariate visualizations and summary statistics that allow you to assess the relationship between each variable in the dataset and the target variable you’re looking at.
- Multivariate visualizations, for mapping and understanding interactions between different fields in the data.
- K-means Clustering is a clustering method in [unsupervised learning](https://developer.ibm.com/articles/cc-unsupervised-learning-data-classification) where data points are assigned into K groups, i.e. the number of clusters, based on the distance from each group’s centroid. The data points closest to a particular centroid will be clustered under the same category. K-means Clustering is commonly used in market segmentation, pattern recognition, and image compression.
- Predictive models, such as linear regression, use statistics and data to predict outcomes.
- **Types of exploratory data analysis**
    1. **Univariate non-graphical.** This is simplest form of data analysis, where the data being analyzed consists of just one variable. Since it’s a single variable, it doesn’t deal with causes or relationships.
    2. **Univariate graphical.** Non-graphical methods don’t provide a full picture of the data. Graphical methods are therefore required. Common types of univariate graphics include:
        1.  Stem-and-leaf plots, which show all data values and the shape of the distribution.
        2. Histograms
        3. box plots
    3. **Multivariate nongraphical:** Multivariate data arises from more than one variable. Multivariate non-graphical EDA techniques generally show the relationship between two or more variables of the data through cross-tabulation or statistics.
    4. **Multivariate graphical:** Multivariate data uses graphics to display relationships between two or more sets of data. The most used graphic is a grouped bar plot or bar chart with each group representing one level of one of the variables and each bar within a group representing the levels of the other variable.

Other common types of multivariate graphics include:

- Scatter plot, which is used to plot data points on a horizontal and a vertical axis to show how much one variable is affected by another.
- Multivariate chart, which is a graphical representation of the relationships between factors and a response.
- Run chart, which is a line graph of data plotted over time.
- Bubble chart, which is a data visualization that displays multiple circles (bubbles) in a two-dimensional plot.
- Heat map, which is a graphical representation of data where values are depicted by color.

### **Visualization**
<img align="center" src="https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/Captura_de_tela_2024-04-29_144137.png"/>


> Data visualization is the representation of data through use of common graphics, such as charts, plots, infographics and even animations. These visual displays of information communicate complex data relationships and data-driven insights in a way that is easy to understand.
> 

<img align="center" src="https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/Captura_de_tela_2024-04-29_144137.png"/>

• **Line charts and area charts:** These visuals show change in one or more quantities by plotting a series of data points over time and are frequently used within predictive analytics. Line graphs utilize lines to demonstrate these changes while area charts connect data points with line segments, stacking variables on top of one another and using color to distinguish between variables.

<img align="center" src="https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/download.jpg"/>


• **Histograms:** This graph plots a distribution of numbers using a bar chart (with no spaces between the bars), representing the quantity of data that falls within a particular range. This visual makes it easy for an end user to identify outliers within a given dataset.

<img align="center" src="https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/download%201.jpg"/>


• **Tree maps,** which display hierarchical data as a set of nested shapes, typically rectangles. Treemaps are great for comparing the proportions between categories via their area size.

<img align="center" src="https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/Treemap-with-measure-name-labels.png"/>

• **Tables:** This consists of rows and columns used to compare variables. Tables can show a great deal of information in a structured way, but they can also overwhelm users that are simply looking for high-level trends.

- **Descriptive Analytics**

![Untitled](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/Untitled.png)

### **Visualization**

![Captura_de_tela_2024-04-29_144137](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/Captura_de_tela_2024-04-29_144137.png)

> Data visualization is the representation of data through use of common graphics, such as charts, plots, infographics and even animations. These visual displays of information communicate complex data relationships and data-driven insights in a way that is easy to understand.

![Captura_de_tela_2024-04-29_144137](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/Captura_de_tela_2024-04-29_144137.png)

• **Line charts and area charts:** These visuals show change in one or more quantities by plotting a series of data points over time and are frequently used within predictive analytics.

![download](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/download.jpg)

• **Histograms:** This graph plots a distribution of numbers using a bar chart (with no spaces between the bars), representing the quantity of data that falls within a particular range.

![download 1](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/download%201.jpg)

• **Pie charts and stacked bar charts:** These graphs are divided into sections that represent parts of a whole.

![1_w2gc_-EXXv-laoJjlD4zmQ](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/1_w2gc_-EXXv-laoJjlD4zmQ.webp)

• **Scatter plots:** These visuals are beneficial in revealing the relationship between two variables.

![download](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/download.png)

• **Heat maps:** These graphical representation displays are helpful in visualizing behavioral data by location.

![download 2](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/download%202.jpg)

### **Machine Learning**

![1_VX3CmoAqxCiqYdZTdCCJ4g](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/1_VX3CmoAqxCiqYdZTdCCJ4g.webp)

**Links de Apoio:**

[Guia Inicial em Machine Learning — PARTE 1](https://medium.com/@clarissatech/guia-inicial-em-machine-learning-parte-1-c78702f341ad)

[Inteligência Artificial — Uma breve história](https://medium.com/blog-do-zouza/intelig%C3%AAncia-artificial-uma-breve-hist%C3%B3ria-51ddbac7a3ae)

[O que é Machine Learning?](https://medium.com/blog-do-zouza/o-que-%C3%A9-machine-learning-5e7e98453985)

[Machine Learning: como funciona, benefícios, tipos e exemplos](https://fia.com.br/blog/machine-learning/)

[O que é Machine Learning? | Google Cloud](https://cloud.google.com/learn/what-is-machine-learning?hl=pt-br)

[O que é machine learning? | IBM](https://www.ibm.com/br-pt/topics/machine-learning)

> Machine learning, a subset of artificial intelligence, is an indispensable tool in the hands of a data analyst. It provides the ability to automatically learn, improve from experience and make decisions without being explicitly programmed.

In the last few decades, the tech advancements in memory storage and process made it possible the creation of products like autonomous cars and recommendation algorithms.

![1_0SA448TiLE5Cw4BoSINfGg](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/1_0SA448TiLE5Cw4BoSINfGg.webp)

**Deep learning and machine learning are not the same thing. While machine learning uses treated data to learn and inform its algorithm, deep learning can process raw data, including text, video, and audio.**

![0_ztayi9rBSOGofDHK](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/0_ztayi9rBSOGofDHK.webp)

- **Supervised machine learning**
    
    > Examples of desired inputs and outputs are presented to the computer, provided by a “teacher”. The goal is to learn a general rule that maps inputs to outputs.

![0_sAJU95sIfJyDdHXD](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/0_sAJU95sIfJyDdHXD.webp)

- **Unsupervised learning**
    
    > No labels are given to the learning algorithm, leaving it alone to find structure in the given inputs.

- **Reinforcement Learning**
    
    ![Untitled 3](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/Untitled%203.png)
    
    > A program interacts with a dynamic environment where it must achieve a specific goal, receiving rewards or penalties based on its actions.

![0_ytxTOMpQuyqO4xZI](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/0_ytxTOMpQuyqO4xZI.webp)

![0_FxZy9fSg8VcaPhIn](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/0_FxZy9fSg8VcaPhIn.webp)

- **Computer vision:** The ability of machines to extract information from visual sources.

![1_TlhEZ0B2T93Zbcu6aVLcug](https://github.com/rafnaves/PraticaDeDados/blob/main/imagens/1_TlhEZ0B2T93Zbcu6aVLcug.webp)

