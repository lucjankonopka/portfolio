# Data Engineering & Analytics — Learning Archive

A collection of projects from my early journey into Data Engineering and Analytics (2021–2023).

These projects were developed through courses, personal experiments, and hands-on learning. While no longer maintained, they remain available as learning resources and a record of where it all started.

For my current work, visit my [GitHub profile](https://github.com/lucjankonopka).
#
### [Web Scrapping - Beautiful Soup](https://github.com/lucjankonopka/web_scrapping)

- Brief overview:   Beautiful Soup tool used to extract data from [official Berlin website](https://www.berlin.de/restaurants/stadtteile/), create a dataset with all restaurants in Berlin and then visualize in form of map of restaurants in Tableau Public.
- Technology used: *python, Beautiful Soup, pandas*
- Final results: [*interactive map of restaurants in Berlin*](https://public.tableau.com/app/profile/lucjan.konopka/viz/RestaurantsinBerlin/RestaurantsinBerlin)

### [Apache Beam - Dataflow Pipeline](https://github.com/lucjankonopka/dataflow_pipeline_bicycles)

- Brief overview:   Apache Beam model was used to extract, transform and load (ETL) data from BigQuery dataset (bigquery-public-data.london_bicycles.cycle_hire) with some detailed informations about London bicycles to obtain some insight on London cycling behaviour. 
The task was to get number of rides from one station to another and present the results in form of text file (start_id, end_id, number_of_rides)
- Technology used: *python, Apache Beam, GCP, Google Cloud SDK Shell*
- Final results: [*output text file with results*](https://raw.githubusercontent.com/lucjankonopka/dataflow_pipeline_bicycles/main/output.txt)
  
### [Apache Spark - Similar Movies Finder](https://github.com/lucjankonopka/spark-movielens)

- Brief overview:   Apache Spark was used to process a large volume of data by using an EMR cluster on AWS. The objective was to analyze 27 million movie ratings for 58,000 movies provided by 280,000 users and find the most similar movies to a selected movie.
- Technology used: *AWS (EMR on EC2, S3), Apache Spark, pyspark, python*
- Final results: [*Top 10 movies similar to "Star Wars: Episode IV - A New Hope"*](https://raw.githubusercontent.com/lucjankonopka/spark-movielens/main/similar_movies.txt)

### [Apache Kafka - Stock Market Simulated](https://github.com/lucjankonopka/kafka_stock_market)

- Brief overview:   In this project, Apache Kafka was used to test the functionality of streaming data transmission.
- Technology used: *AWS (EC2, S3, Crawler, Amazon Athena), python*
- Outcome: Continuously uploaded data to an S3 bucket during the program's execution

### [Google Data Analytics Capstone: Complete a Case Study](https://github.com/lucjankonopka/cyclistic_case_study)

- Brief overview: Following case study was completed as part of the [Google Data Analytics Certificate](https://www.credly.com/badges/d8457d2e-06e4-4142-8ea1-4cfd52f24c67/linked_in_profile).
- Methodology: data preprocessing, data cleaning, data analysis, visualization, making conclusions, creating a strategy proposal
- Technology used: *python, pandas, matplotlib, numpy, seaborn*
- Final results: [*analysis & visualisation*](https://github.com/lucjankonopka/cyclistic_case_study/blob/main/How%20Does%20a%20Bike-Share%20%20Navigate%20Speedy%20Success.pdf)

# 
[LinkedIn](https://www.linkedin.com/in/lucjankonopka/) · [GitHub](https://github.com/lucjankonopka) · [Tableau](https://public.tableau.com/app/profile/lucjan.konopka)


