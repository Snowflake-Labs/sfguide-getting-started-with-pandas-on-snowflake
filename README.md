# Getting Started with pandas on Snowflake

## Overview
pandas is the go-to data processing library for millions worldwide, including countless Snowflake users. However, pandas was not built to handle data at the scale organizations are operating today. Running pandas code requires transferring and loading all of the data into a single in-memory process. It becomes unwieldy on moderate-to-large data sets and breaks down completely on data sets that grow beyond what a single node can handle. 

With [pandas on Snowflake](https://docs.snowflake.com/developer-guide/snowpark/python/snowpark-pandas), you can run your pandas code directly on your data in Snowflake, with all the processing pushed down to run in a distributed fashion in Snowflake. Just by changing the import statement and a few lines of code, you can get the same pandas-native experience you know and love with the scalability and security benefits of Snowflake. Your data never leaves Snowflake, and your pandas workflows can process much more efficiently using the Snowflake elastic engine. This brings the power of Snowflake to pandas developers everywhere.

This quickstart will focus on getting started with Snowpark pandas and demonstrates the scalability benefits of using pandas on Snowflake.

## Step-by-Step Guide
For prerequisites, environment setup, step-by-step guide and instructions, please refer to the [Quickstart Guide](https://quickstarts.snowflake.com/guide/getting_started_with_snowpark_pandas/index.html).
