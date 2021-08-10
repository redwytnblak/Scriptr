# Scriptr

This is a simple application that has two versions: Lite and Zoom. 

Scriptr Lite
Lite will require manual user input of the Template, Regex, Input, and Output and generate a groovy script from a template to search an Input for the given Regex. 

Scriptr Zoom
Zoom will allow a user to specify a CSV file containing 


Parameters: 

Template: Single or Multi hit Groovy script.

Regex: Regex to search.
  Note: Regex in Groovy will need to be encapsulated in double quotes " " and all backslashes used will need to be duplicated. 
    eg. "Regex \\ here"
 
 Input: Object being searched. 
 
 Output: The output object of the script.
