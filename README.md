# Gradebook_Seeder

In this project, I created a gradebook based on a fictional school, with the end goal of building a dashboard for tracking student grades and progress. 

To begin, I needed to generate the data, as I had no access to a gradebook. I used the random and names libraries in Python to generate random data. Then, using Pandas, I compiled dataframes from that data. I created a list dictionary containing all of the classes offered at "Jeff High School", then randomly generated the student body. I then assinged each of the 2000 fictional students a transcript, composed of 14 classes. Finally I compiled my results in a large dataframe. To help calculate GPA's, I also created a credit-hours dataframe.

My next step was to import the data into Google Cloud Platform using the os and BigQuery libraries. Once my data was in GCP, I used SQL to Create tables from my database, Read and Update the tables, and Delete unnecessary information. 

My last step was to create a dashboard from the tables in my database to allow my (fictional) administrators, parents and teachers to view the academic performance of individual students, classes, or groups to allow them to make decisions about next year's curriculum. This was done with Data Studio, which connected to my BigQuery tables.

Once my project was complete, I put together a Lucid Chart to illustrate the steps of this project.
