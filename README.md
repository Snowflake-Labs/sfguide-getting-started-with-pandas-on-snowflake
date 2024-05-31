# Getting Started with Snowpark pandas

## Overview
pandas is the go-to data processing library for millions worldwide, including countless Snowflake users. However, pandas was never built to handle data at the scale organizations are operating today. Running pandas code requires transferring and loading all of the data into a single in-memory process. It becomes unwieldy on moderate-to-large data sets and breaks down completely on data sets that grow beyond what a single node can handle. We know organizations work with this volume of data today, and Snowpark pandas enables you to execute that same pandas code, but with all the pandas processing pushed down to run in a distributed fashion in Snowflake. Your data never leaves Snowflake, and your pandas workflows can process much more efficiently using the Snowflake elastic engine. This brings the power of Snowflake to pandas developers everywhere.

This quickstart will focus on getting started with Snowpark pandas, and enable you to perform common pandas operations on huge volumes of data using the power of Snowflake.

## Step-by-Step Guide
For prerequisites, environment setup, step-by-step guide and instructions, please refer to the [Quickstart Guide](https://quickstarts.snowflake.com/guide/getting_started_with_snowpark_pandas/index.html?index=..%2F..index#0).