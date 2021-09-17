# CovidApp

Repository: https://github.com/healthyBeaver/CoronaTracker

This app is developed by Hyukjoon Yang and Jeijun Lee.

Motivation
As I and Jeijun Lee are international students, it is inevitable for us to visit countries.
However, it was difficult for us to check COVID status for each country we have to visit.
Furthermore, even if we visited national government websites, they are written in their languages.
Therefore, we decided to develop a mobile app to help us to check the COVID status of the world.


How it works
It uses AWS ad the main database server.
It retrieves data from online API for real-time data about COVID around the world.
After retrieving all the data, it updates data in the database with the new data from the API.
User will be able to see the COVID status around the world by graph and charts.
By doing so, when the user has to go abroad, he/she can use the application to check COVID status in the country the user is going to.

Note
Currently, the database in AWS is stopped because it costs a lot to maintain the server.
