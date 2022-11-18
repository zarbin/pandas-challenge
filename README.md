# Pandas Challenge - Module 4 Homework
Module 4 Challenge for UTA DataViz Bootcamp
11/17/2022

# PyCitySchools

Please note I used the Canvas  PyCitySchools_starting.ipynb file that did not contain any code or comments in it other than the first cell to import the CSV files.  I found out the day before the homework was due there was a much more complete starter file on Gihub in the Homework4 folder repository.  It explains why my code may look different and be inconsistent as I essentially started from scratch on this assignment. 

The purpose of this assignment is to read two external .csv files and complete data analysis on student level data and school level data.  
* schools_complete.csv
* students_complete.csv

**After the merge**
![image](https://user-images.githubusercontent.com/36682023/202631240-2539c104-2296-4993-85c0-9978b5aa72cb.png)




**PyBank Results Screenshot**

![image](https://user-images.githubusercontent.com/36682023/200943430-01eed6cb-30b1-4eec-8e66-1ec45e7bd276.png)

# PyPull

The purpose of this assignment is to read in an external CSV file, Loop through each row, and produce polling results that are outputted to both the termainal and into a text file. 

Using a dictionary to store a key pair that tracks unique political contender and their respective vote count seems like an elegant and effecient solution to me. 

```python
#Use dictionary to tally votes per candidate as we loop through  
#check if candidate is in dictionary.  If not add new dict key, if present increment their vote count
if row[2] not in vote_results.keys():
  vote_results[row[2]] = 1
else:
  vote_results[row[2]] += 1
```

**PyPull Results Screenshot**

![image](https://user-images.githubusercontent.com/36682023/200943598-c12c34c6-648b-4ed8-b222-1ccaeee84321.png)
