# README #

### What is this repository for? ###

This README tells you how to process Balmorel results by sql-queries that can be executed from a python script or VBA with the help of the files in this repository.

### How do I get set up? ###

* Convert the Balmorel output gdx-file to a sqlite file with the ending .db following this [explanation of using gdx2sqlite](https://www.gams.com/latest/docs/userguides/mccarl/gdx2sqlite.htm). More detailed explanation: Open a terminal (in windows: search for 'cmd'). Then type
cd.. <Enter>
cd.. <Enter>
cd win64 <Enter>
cd 24.4 <Enter>
gdx2sqlite -i <filepath of the gdx-file> -o <filepath of the sqlite-output-file> 
e.g. gdx2sqlite -i c:\users\frwi\documents\...\BASE-results.gdx -o c:\users\frwi\documents\...\BASE-results.db

* Clone this repository
* Open either the Python script (.py) on your computer or open the VBA-file, press the button, choose the path of the .db file and happily play with the results

### Contribution guidelines ###

* To be configured
* Still missing: Choice of not executing all sql-queries (takes time) by ordering blocks of sql-queries and necessary in any case and other sql-queries / pictures for the python version / Make it run for postgreSQL-database

### Who do I talk to? ###

* Hardi or Frauke
* others?