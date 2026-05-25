# How to run

1. Copy the datasets into your working directory using these commands:

```
aws s3 cp "s3://[S3 bucket]/yellow_tripdata_2026-01.parquet" <WORKING_DIR>/
aws s3 cp "s3://[S3 bucket]/green_tripdata_2026-01.parquet" <WORKING_DIR>/
```

2. Update the output_base S3 path to point to your bucket.

3. Connect to your python kernel and run all the code in the notebook.

# Generative AI Disclosure
Tools Used: ChatGPT

Key Prompts: I used ChatGPT to clarify errors and debug issues with running pyspark regression and S3 uploads using PySpark's built in write method. I also used it for help with discovering PySpark dataframe methods I could use and on writing an alternative function for uploading the parquet files to S3. 

What I changed and how I verified: All code was implemented by me and suggestions from generative AI were verified by running the code, and cross checking with documentation and other online sources.