# Netbackup-S3-storage-system

Netbackup-S3 separates "data" and "metadata" storage, files are split into chunks and stored in object storage like Amazon S3, 
and the corresponding metadata can be stored in various databases such as Redis, MySQL, TiKV, SQLite, etc., based on the scenarios and requirements.

It provides rich APIs for various forms of data management, analysis, archiving, and backup. It can seamlessly interface with big data, machine learning, 
artificial intelligence and other application platforms without modifying code, and provide massive, elastic and high-performance storage at low cost. 
