# Overview

This folder is to showcase the work and learning I am trying to make in a library named Polars for Data Analysis. The purpose of this is to show firstly the basic commands to work with polars. We have a dataset which has 8 years of data of the standings in the Soccer Premiere League from England, we have a csv file for each year. We will append them and try to have some summary questions that will help us answer some questions. We will try to use the filter, sort, aggreagate, distinct.

# Data Analysis Results

## Since we have relagation and promotion how many unique teams we had during the 8 seasons. (distintct function)

Answer 32 teams

## Now if we were interested on this 32 teams see their goal difference (goals in favor and goals against) which team would have the most goals and how many

Manchester City with 450 goals 

## Finally if you were to aggragate all the stats into one data frame to see which teams had the most points during the 8 seasons who would be the first 3 teams with the most points

│ Manchester City     ┆ 674          │

│ Liverpool           ┆ 622          │

│ Chelsea                 ┆ 587

# Development Environment

Polars is a powerful data manipulation library in Python designed for fast, efficient, and expressive data operations. It provides a DataFrame API that is similar to Pandas but optimized for performance on large datasets. With Polars, you can perform various data transformations, aggregations, filtering, and more.

Lazy functions in Polars offer a lazy evaluation mechanism, enabling deferred execution of operations. Rather than immediately executing operations, lazy functions build an execution plan that is optimized and executed when necessary. This laziness allows for efficient execution and optimization of complex data workflows, minimizing unnecessary computations and enabling better performance. It also provides an opportunity for optimization and parallelism, especially when dealing with large-scale data processing (BIG DATA).


# Useful Websites

{Make a list of websites that you found helpful in this project}
* [Polars Library](https://pola-rs.github.io/polars-book/user-guide/)
* [Get started with polars with towards Data Science](https://towardsdatascience.com/getting-started-with-the-polars-dataframe-library-6f9e1c014c5c)

# Future Work

One of my main interests for learning polars is because this library
can read a type of files named parquet files. Parquet files are columnar storage file format designed for efficient data storage and processing, they can contain millions of rows of data in little space of memory, which is very optimal when we are procesing big data.
So here is the list to learn more in the future:

* Handling parquet files.
* Understanding the lazy APIs.
* How do you use window functions.