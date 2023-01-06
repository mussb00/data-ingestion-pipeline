# data-ingestion-pipeline

A simple data ingestion pipeline to read a large dataset (>2GB). Dask and chunking in pandas are used to compare the processing and computational efficiencies of each on larger datasets. A validation script ensures data adheres to a YAML configuration file and the file is then stored in pipe-separated text file for further use.
