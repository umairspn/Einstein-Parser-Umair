# Einstein-Parser-Umair
This repository includes a Config Parser developed in Python from scratch. It takes a config file and generates a hash for the variable and variable name parsed from the given config file. 

### Language Used
Python Programming Languge 

### Tool Used
Jupyter Notebook 


## Task Description 
Create a parsing tool that takes the example config file (provided below) and turns it into a usable object in the language of your choice (hash, JSON object, associative array, class, etc). 


### Given Solution
Converts a config file into a hash (dictionary in Python) as the key value paris where:
Key = Variable 
Name = Value (with valid type) 

### Complexity
Time Complexity: O(N) since we iterate only once over the given file 

Space Complexity: O(N) since we store the entire config file into a Hash/Dictionary 

### Code Optimization 
The code is optimized to a certain extent in terms of space and time complexity as our algorithm does not store any variables 
during the iterations/processing. Though, since we need to store the config file items into a Hash/Dict, the overall complexity reaches O(N). 
As we read from the config file, we process each line/string from the given file on the go and update it into the Hash/Dict. 

### Possible Extensions/Clarifications
The code is written in a way that based on further requriements, it can be easily updated. 
