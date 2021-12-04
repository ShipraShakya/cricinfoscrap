# cricinfoscrap
Cricket Website Scrapping
I wrote a script using axios, jsdom, excel4node and pdf-lib which scraps WorldCup 2019 scorecards from cricinfo and stores that in excel sheets and pdf form. The purpose of writing this script was to get familiar with using npm modules, promises in JavaScript, learn how to extract information and get experience with js, A very good reason to ever make a project is to have good fun.

I created a excel file using excel4node, where pages are divided acoording to team's name, and containing that team's match information.
Created a PDF file using pdf-lib library, having team name, opponent,score and result.
To create the PDF file template used is: 

# How to do this activty in your system:
1. create a folder and run command npm init -y in the terminal, the terminal location must be of that folder.
2. copy and paste or download the code by downloading zip folder.
3. make sure to delete the matches.json, teams.json, Worlsdcup.csv, data folder.
4. open the terminal and run given commands 
a) npm init -y 
b) npm install minimist
c) npm install axios
d) npm install jsdom
e) npm install excel4node
f) npm install pdf-lib

after running all the commands run this command:  main.js --excel=Worldcup.csv --dataFolder=data --source=https://www.espncricinfo.com/series/icc-cricket-world-cup-2019-1144415/match-results 


Activity done.
after running above command a new data folder should be generated named as data.
and new files JSON files should be generated.
