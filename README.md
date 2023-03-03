# Snowpark Handson-Lab for Credit Card Approval Prediction
This repository is a fork from Data Scientists at Solita Sweden.

The notebooks in here contains resources to get first handson experience with Snowpark.

## Here are some comments 

- The data exploration is mostly showing how the Snowpark Pandas API works. The idea is that you can write Pandas-ish code when working on tables in a database. This is very similar to how it works in `siuba` and `dplyr`. I have also included some comparisons to ordinary Pandas so we can see the differences in syntax and speed (hint for small data pandas is faster).

- We created a trial warehouse for this 

- The modelling code consists mostly of wrapping Python-code into UDFs that you then use to execute the training and scoring of models in Snowflake.

Please follow the steps outlined in this Quickstart to run this Handson-Lab:
[Quickstart](https://quickstarts.snowflake.com/guide/getting_started_snowpark_machine_learning/index.html)