# Hadoop String Sorting


## Purpose 

The purpose of this project is to enhance the learning outcome by doing a string sort using HDFS. 

## Code

All the code are in the folder [code](code), the code is dividing into 3 parts. the code was written in Java.

- [Data Generation](code/StringGen)
  - Using RandomGenerator program, it randomly generates strings with 97 characters each line. 
  - Combines the data and output to the file for sorting.
- [Data Sort](code/StringSort)
  - Sorts data using string sort.  
  - The whole Sorting process is done using Hadoop map-reduce.
- [Data Post - Validation Sort](code/StringValidate)
  - Given the order of sorting used in sorting phase, it validates sorted data as per sorting order mentioned.
  - The whole Sorting process is done using hadoop map-reduce.

## Hadoop configuration files

We are using `hadoop 2.8.2` in `macOS HighSierra (Version 10.13.3)`. all the config files are stored in the folder [HadoopConfig](HadoopConfig)

