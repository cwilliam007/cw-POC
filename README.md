# cw-POC
POC for Talend

Use Case #1 
  - CDC Kafka stream from IBMi via IBM IIDR 
  - 1 to 10 tables
  - Starting with RCTCDP table
  - Implement Key managment 
  - Implement Segment/Bucket and Partition
  Note: replace current CDC file based to Kafka stream
  
Use Case #2
  - Medical Claims 
  - Source from DB2 via Sqoop to HDFS (Data lake)
  - DataLake to curated layer
  - Implement Key managment 
  - Implement Segment/Bucket and Partition
  - Lookup to apply Enterprise ID
  Note: replace current custom coding for DataLake to currated layer
