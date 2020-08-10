# WordCount
WordCount Map Reduce Example

After each run delete the output directory to run the code again
      hadoop fs -rm -r /user/hadoop/wordcount/output

To run the code
 hadoop jar wc.jar WordCount /user/hadoop/wordcount/input /user/hadoop/wordcount/output

To list and display output
 hadoop fs -ls /user/hadoop/wordcount/input
 hadoop fs -ls /user/hadoop/wordcount/output
 hadoop fs -cat /user/hadoop/wordcount/output/part-r-00000

