---
name: Keven Vega
course: cis106
semester: Fall 2023
---


# Week Report 7

## Cat Command

*Description
    *The cat command is used for displaying that content of a file
*Usage
    *cat + option +files(s) to display
*Examples
    *Display the content of a file located in the pwd
    cat todo.lst
    *Display the content of a file using absolute path
    cat ~/Documents/todo.lst

## Tac Command

*Description 
    *The tac command is used for displaying the content of a file in reverse order
*Usage
    *tac + option + files(s) to display
*Examples
    *Display the content of a file located in the pwd
    tac todo.md
    *Display the content of a file using absolute path
    tac ~/Documents/todo.md

## Head Command 

*Description 
    *The head command displays the top N number of lines of a given file
*Usage
    *head + option +file(s)
* Examples
    *Display the first 10 lines of a file 
    head ~/Documents/Book/dracula.txt
    *Display the first 5 lines of a file
    head -5 ~/Documents/Book/dracula.txt

## Tail Command 

*Description
    *The tail command displays the last N number of lines of a given file
*Usage
    *tail ~/Documents/Book/dracula.txt
*Examples
    *Display the last 10 lines of a file
    tail ~/Documents/Book/dracula.txt
    *Display the last 5 lines of a file
    tail -5 ~/Documents/Book/dracula.txt

## Cut Command 

*Description 
    *The cut command is used to extract a specific section of each line of a file and display it to the screen
*Usage
    *cut + option + file(s)
*Example
    *Display a list of all the users in your system
    cut -d ':' -f1 /etc/passwd
    *Display a list of all the users in your system with their login shell
    cut -d ':' -f1,7 /etc/passwd

## Paste Command 

*Description
    * the paste command is used for joining files horizontally in columns
*Usage
    *paste + options + files
*Examples
    *Merge two files
    paste users.lst ip_address.lst
    *paste -d ":" users1.1st ip_addresses.1st

## Sort Command 

*Description 
    * The sort command is used for sorting files
* Usage
    * sort + option + file
* Example
    * Sort a file
    sort users.lst

## Wc command

*Description
    *The wc command is used for printing the number of lines, characters and bytes in a file
*Usage
    *Display the number of characters in a file
    wc + option + file(s)

    *Display the number of lines in a file
     wc -m users.txt
    *Display the number words in a file
    wc -w users.txt

## tr command 

*Description
    *The tr command is used for translating or deleting characters from standard output
*Usage
    *Standard output | tr + option + set + set
*Examples
    *Translate one character to another
    cat file.txt | tr '.' ','
    *Translate white space into tabs
    cat file.py | tr "[:space:]" '\t'
    *Translate tabs into space
    cat file.py | tr -s "[:space:]" ' '

## diff command

*Description
    *The diff command compares files and displays the differences between them
*Usage 
    *diff + option +file1 + file2
Examples
    *Display the differences between two files
    diff cars.csv cars-backup.csv
    *Display the differences between two files in a column format
    diff -y cars.csv cars-backup.csv

## grep command 

*Description
    *Grep is used to search text in given file. Grep works line by line basis
*Usage 
    *grep + option + search criteria
*Examples
    *Search any line that contains the word "dracula" in the given file
    grep 'dracula' ~/Documents/dracula.txt

## awk command

*Description
    *awk is a scripting language used for processing and displaying text
*Usage
    *awk + options + {awk command} + file + file to save (optional)
*Example 
    *Print the first column of every line of a file
    awk '{print $1}' ~/Documents/Csv/cars.csv
    *Convert the first field to upper/lower case
    awk -F: '{print toupper($1)}' /etc/passwd
    *Prints the length of a line
    awk '{print length($0)}' /etc/passwd
    *Print specific fields based on a command output
    ls -1hF Documents/ | awk 'BEGIN { printf "%s\t%s\n", "Size","Name"} {print $5,"\t",$9}'
    *Print specific fields with a head of the /etc/passwd file
    awk -F: 'BEGIN { printf "%s\t\t%s\n", "User","Shell"} {print $1,"\t",$7}'

## sed command

*Description 
    *SED is a stream editor that perform operations on files and standard output
*Usage
    *sed options + sed script + file
*Example
    *Replacing a string in a given file
    sed 's/pizza/rice/' shopping-list.1st
    *Replacing the number of occurrences of a pattern in a file
    sed 's/pizza/rice/4' shopping-list.1st
    *Replacing all the occurrence of the pattern in a file
    sed 's/pizza/rice/g' shopping-list.1st
    *Replacing string on a specific line number
    sed '3 s/pizza/rice/' shopping-list.1st
    *Replacing string on a range of lines
    sed '1,3 s/pizza/rice/' shopping-list.1st



  

