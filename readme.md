For standalone mode:
requirements:
spark==3.0.1
findspark==1.4.2
pandas==1.1.3
numpy==1.19.2
matplotlib==3.3.2
nltk==3.5
Steps to run:
1. Open jupyter notebook.
2. create spark session.
3. run the notebook cells.
4. In the content based filter, at the end of the notebook input any Track ID from the lyrics_sample.csv.


For pseudo distribution mode:
requirements:
spark==3.0.1
Hadoop==3.2.1
Hive==3.1.2
findspark==1.4.2
pandas==1.1.3
numpy==1.19.2
matplotlib==3.3.2
nltk==3.5

Steps to run:
1. move the datasets into HDFS cluster.
2. open jupyter notebook.
3. create spark session.
4. run the notebook cells.
5. In the content based filter, at the end of the notebook input any Track ID from the lyrics_sample.csv.

