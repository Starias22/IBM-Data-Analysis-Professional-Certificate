# Module 1: Introduction to Data Visualization Tools

## Welcome to the Course


## Introduction to Data Visualization

### Overview of Data Visualiztion

- Graphical representation of data and information
- Can take a variety of forms: from basic charts and graphs to more complex interactive dashbord, mps and infographics 

#### Why data visualization?

- Easily understand data
- Communicate insights

#### Fields

- Business and finance
- Healthcare
- Education
- Government
- Research and Science
- Entertainment

#### Best practices

- Choosing the appropriate type of Visualization
- Keep it simple
- Use clear Labeling and Formatting
- Keep visualization focused on the main points
- Consider the audience: the visualization should be tailored to user needs
- Not that :
    - Less is more efffective
    - Less is more attractive
    - Less is more impactful

### Types of Plots

#### Line plot

- aka a line chart
- represents data as e serie of data points connected by straight lines
- Use case:
    - **display trends over time**
    - **compare data sets** with  a continous independant variables such like age or time
    - **illustrate cause-and-effect relationship** such as production quantities based on rainfall
    - **Visualize continous data** like height measurement over time

#### Bar plot

- aka bar chart
- display data using rectangular bars where the height or lenght of the bar represents the magnitude of the data
- Can be oriented horizontallly or vertically(vartical or column bar chart)
- Use case:
    - Compare different categories or groups
    - Display discrete data that has distinc categories: comparing sales revenues(discrete values) by products(categories)
    - Show how different categories contribute to a whole: sales percentages, budget allocation
    -  Visualize data that you can easily rank: displaying the bestselling books in the market

#### Scatter plot
- Display values for two variables using cartesian coordinates
- Use case: 
    - Study the relationship between two continous variables: temperature vs energy consumption
    - Investigate patterns or trends in data: house prices vs size
    - Detecting outliers
    - Identy clusters or groups in the data
    - Explore complex data

#### Box plots
- aka a box or whisker plot
- Display the distribution of the data along with key statistical measures
- Use case:
    - compare the distribution of a continous variable accross different categories or groups: Employees salaries accross departments
    - Examine the spread and skewness of a dataset, visualizing quantiles and outliers
    - Identify and analyze potential outliers
    - Visualize summary statistics such as median, quantiles, range
    - Compare distributions of multiple variables in datasets

#### Histogram
- Representation of the distribution of the dataset showing the frequency or relative frequency within intervals
- Use case:
    - Understand data distribution
    - Visualize the shape of the dataset
    - Acess skewness of the data
    - Show data variability and spread

### Plot Libraries

- Matplotlib
    - General purpose plotting library
    - Integrates well with numpy, pandas, seaborn, plotly
- Pandas: Provide Integrated plotting features for data analysis
- Seaborn: specialized library for statistical visualization
- Folium: for maps creation
- Plotly: interactive and dynamic data visualization library
- PyWaffle: visualize proportianal representations using squares or rectangles

### Introduction to Matplotlib 

One of the most used data visualization libraries in Python

#### Matplotlib architecture

3 mains layers
1. The backend layer
2. The artist layer
3. The scripting layer

![alt text](image.png)

![alt text](image-1.png)

#### Components of a plot
- axis
- title
- legend
- etc

### Basic Plotting with Matplotlib
Created by Jonh Hunter
matplotlib inline is used to enforce matplotlib showing the figure in the browser, not in a news popup window
matplotlib notebook is used to apply some modifications such as title, legend to a figure that is already rendered. Anew figure is rendered only if it didn't exist yet.

It supports Pandas

openpyxl is used to extract data from excel spreasheets

### Dataset on Immigration to Canada

Each row represents a country

![alt text](image-3.png)

![alt text](image-4.png)

![alt text](image-5.png)
### Line Plots

![alt text](image-2.png)
