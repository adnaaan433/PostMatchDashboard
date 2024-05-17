# PostMatchDashboard
Hi there, I am Adnan, data analysis enthusiast. In this repository I have uploaded the code for making Post Match report.

Requirments:
1. the match report you want to get, you have to find that match in (http://whoscored.com) website and clicking the match center, you have to download the html file (just click CTRL+S, and it will download the html file of that page)
2. you need to collect the home and away team's xG and xGOT values from any sources and have to put manually in the code

User's Guideline:
1. download the PostMatchDashboard.ipynb file
2. upload and open it on google colab
3. run the cells under 'Libraries and Packages'
4. then upload the match html file you have downloaded from Whoscored website
5. right click on the file and copy path
6. paste the file path on the first cell under 'EventDataScraping' where denoted whith hashtag 'Put the match html file path here', and run the cell
7. Paste the home and away team's xG and xGOT values in the next cell and run
8. then runnuing the remaining cells will give you the output Post Match Reports
