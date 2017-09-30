Python Implementation of Apriori Algorithm
==========================================

List of files
-------------
1. apriori.py
2. data.csv
3. README(this file)

How to Run the code
-----
To run the program with dataset provided and default values for *minSupport* = 0.15 and *minConfidence* = 0.6

    python apriori.py -f data.csv

To run program with dataset

    python apriori.py -f data.csv -s 0.17 -c 0.68

Best results are obtained for the following values of support and confidence:

Support     : Between 0.1 and 0.2

Confidence  : Between 0.5 and 0.7
