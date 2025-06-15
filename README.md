# TASK 1
# BIG-DATA-ANALYSIS

 *COMPANY*: CODTECH IT SOLUTIONS
 
 *NAME*: ASMITHA SRI R
 
 *INTERN ID*: CTOBDG1383
 
 *DOMAIN*: DATA ANALYTICS
 
 *DURATION*: 8 WEEKS
 
 *MENTOR*: NEELA SANTOSH

 CODE OF THE TASK: https://nbviewer.org/github/Asmitha-GitHub/BIG-DATA-ANALYSIS/blob/main/BIG_DATA_ANALYSIS.ipynb#

 DESCRIPTION OF TASK 1: During my internship with CodTech IT Solutions under the guidance of my mentor Neela Santosh, I was assigned a task in Big Data, specifically on PySpark. My main task was to execute a complete pipeline of data analysis utilizing PySpark in Google Colab. I used the Flight Delay and Cancellation Dataset. The dataset provided had data for flights and delays for a huge number of scheduled commercial flights.

To start with, I set up the Spark environment in Google Colab. This involved the installation of Java, download of a suitable Apache Spark version (Spark 3.3.0 with Hadoop 3), and establishment of environment variables. I also used the `findspark` package to integrate Spark with the Python ecosystem without any issues. Upon finishing the setup process, I mounted Google Drive so that I could access the dataset uploaded in CSV format. The information included some columns such as flight date, airline name, source and destination, scheduled and actual departure and arrival time, delay time, reasons for cancellations, etc.

After having loaded data into a Spark DataFrame, I performed schema inspection to determine the structure and data type of each column. It helped me identify which fields would be beneficial for analysis. Exploratory data analysis (EDA) came next, where I prioritized key insights like the following:

- Which airline had the maximum delays
- Average delay times for each airline
- Most common cancellation reasons
- Leading departure cities
- Correlation between weather and delays

I used a mixture of PySpark DataFrame operations such as `.groupBy()`, `.agg()`, `.filter()`, and `.orderBy()` to extract and condense important information. In some parts of the notebook, I converted Spark DataFrames to Pandas for display purposes. Using matplotlib and seaborn, I produced bar plots and line plots to show delay patterns in airlines and airports.

The whole analysis was performed efficiently making use of the distributed computing power of PySpark. Not only did this give me firsthand experience in handling big data, but it also improved my understanding of handling Spark in cloud-based environments like Colab. I understood handling Spark sessions, data loading efficiently, runtime error debugging, and interpreting analytical outputs.

OUTPUT:

![Image](https://github.com/user-attachments/assets/208d602d-5cab-4578-bd06-b5fcc5499608)
