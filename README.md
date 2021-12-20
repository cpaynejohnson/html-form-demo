### Read me ###

1) npm install
2) We left some comments to help you understand some of the weird parts of handlebars.
3) study and experiment with this code base

# Verizon Warehouse and Inventory Management App
![Screenshot of wireline]<img src=".png" width="500" height="500" />
![Screenshot of wireline]<img src=".png"/>

# Project Description

The goal of this project is to create an app that allows users to efficiently manage our warehouse database.  There are 2 user types for our app: managers and employees.

Managers are able to:
1. Log into a password protected manager view.<br>
2. Add and remove warehouses from the database.<br>
3. Add and remove warehouse employees from the database.<br>
4. Update the worksite of a given employee.<br>
5. View a record of employee activity including timestamps of all items they added or removed from a warehouse.<br>

Employees are able to:
1. Log into a password protected employee view.<br>
2. Add and remove palettes and boxes from the database.<br>
3. Receive alerts when a palette is empty and must be removed.<br>
NOTE: Employees are associated with a specific worksite and may only view, add or remove inventory from that site.<br>


# Technologies Used:
<ul>
<li><a href="https://code.visualstudio.com/">Visual Studio Code</a></li>
<li><a href="https://nodejs.org/">Node.js</a></li>
<li><a href="https://jestjs.io/">Jest</li>
<li><a href="https://sequelize.org/">Sequelize</li>
<li><a href="https://www.sqlite.org/">SQLite 3</li>
<li><a href="https://expressjs.com/">Express.js</li>
<li><a href="https://www.postman.com/">Postman</li>
<li><a href="https://drawio-app.com//">Draw.io</li>
<li><a href="https://moqups.com/">Moqups</li>
<li><a href="https://www.atlassian.com/software/jira">Jira</li>
</ul>

# Project Planning
![ERD diagram]<img src="express-movie-ERD.png" width="600" height="500" />
![kanban board]<img src="https://raw.githubusercontent.com/cpaynejohnson/express-movie-database/main/public/kanban.png">

# Testing Results
<img src="test_file.png" width="500" height="500" />
<img src="test_report.png" width="500" height="500" />

# Getting Started

Fork and clone this repository then run <code class="w3-codespan">npm install</code> to add the relevant dependencies. Run <code class="w3-codespan">npm run test</code> to seed the database and confirm tests pass. Finally, run <code class="w3-codespan">npm run app.js</code> to run the express server and interact with the Routes using <a href="https://www.postman.com/">Postman</a>.


# Contribution Guidelines

To make suggestions, please create a new issue on this repo.

# Authors and acknowledgments

<iframe src="https://giphy.com/embed/m0Qk8qf1KyW3Kcgmjp" width="480" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/jv-agency-teamwork-jv-agency-jvagency-m0Qk8qf1KyW3Kcgmjp">via GIPHY</a></p>
<li>Iyanna Bell - Front End Developer</li>
<li>Muneer Malik - Backend Developer</li>
<li>Crystal Johnson - Scrum Master</li>

Thank you to Micheal Dunn-O'Connor for all of his assistance! 
