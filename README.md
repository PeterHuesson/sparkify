<h1>Installation</h1>
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using:

- Python 3.6
- Spark 2.4

<h1>Data</h1>
I used the small and medium size data provided by udacity.

<h1>Structure</h1>
<code>
root
 |-- artist: string (nullable = true)
 |-- auth: string (nullable = true)
 |-- firstName: string (nullable = true)
 |-- gender: string (nullable = true)
 |-- itemInSession: long (nullable = true)
 |-- lastName: string (nullable = true)
 |-- length: double (nullable = true)
 |-- level: string (nullable = true)
 |-- location: string (nullable = true)
 |-- method: string (nullable = true)
 |-- page: string (nullable = true)
 |-- registration: long (nullable = true)
 |-- sessionId: long (nullable = true)
 |-- song: string (nullable = true)
 |-- status: long (nullable = true)
 |-- ts: long (nullable = true)
 |-- userAgent: string (nullable = true)
 |-- userId: string (nullable = true)
 
 </code>
 
<h1>Project Motivation</h1>
This is the capstone project of a udacity nanodegree.
In this project we build a machine learning algorithm to best predict customers who might end their service in our fictional streaming service.

<h1>Results</h1>
I published the full results of my findings in this post on medium:
https://medium.com/@peter.huesson/how-you-never-lose-a-customer-again-e35928a227e8

<h1>Licensing, Authors, Acknowledgements</h1>
Must give credit to Udacity for the Sparkify Event data.

- Spark MLlib: Main Guide
- udacity
