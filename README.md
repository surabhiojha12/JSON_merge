# JSON_merge

Overview
----------
JSON_merge.py is a program that can merge a series of files containing JSON array of Objects into a single file containing one JSON object.

Features
----------
* It can merge any kind of JSON array of Objects(generic solution).
* It also supports non-English characters (like &$@! etc).
* It works with multiple JSON array of Objects.

Time Complexity
----------------
The solution uses hash map technique. The solution is implemented in python so dictionary is used for the same.
* #### Searching in Dictionary (hash map)
Average Time: O(1) <br/>
Worst Case: O(n)  <br/>
* #### Inserting a new entry in Dictionary (hash map)
Average Time: O(1) <br/>
Worst Case: O(n)  <br/>
* #### Iterating the Dictionary (hash map)
Average Time: O(n)  <br/>
Worst Case: O(n)  <br/>
* #### Appending values in a list
Average Time: O(1)  <br/>
Worst Case: O(1)  <br/>

* #### General analysis
If there are n root keys in total(count of all root keys from all input files) and each root keys contains m objects in its value
then, <br/>
<b> Average time complexity of merging is </b> : O(n * m) as inserting and searching time is O(1) and iterating time of objects in root keys value is O(m) and iterating time of n root keys is O(n)

Input File Image
---------------
* #### Data1.json

![Data1](data1.png?raw=true "Optional Title")
-----------------------------------------------

* #### Data2.json

![Data2](data2.png?raw=true "Optional Title")
-----------------------------------------------

* #### Data3.json

![Data3](data3.png?raw=true "Optional Title")
-----------------------------------------------

Output File Image
---------------
* #### Merge1.json

![Merge1](merge1_1.png?raw=true "Optional Title")
-----------------------------------------------

* #### Merge2.json

![Merge2](merge1_2.png?raw=true "Optional Title")
-----------------------------------------------

