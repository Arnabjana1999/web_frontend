# web_frontend
## Front_end tools using bootstrap and angular/react

npm init 

npm install lite-server --save-dev

Change the package.json file. Add the following inside "scripts" (which contains "test" currently)
"start": "npm run lite"
"lite": "lite server"

Make a dummy html file (index.html)
Changes reflected in real-time (without refreshing the browser)

Installing Bootstrap4:

npm install bootstrap@4.0.0 --save

Bootstrap requires installation of the following peers:

npm install jquery@3.3.1 popper.js@1.12.9 --save

bootstrap class "jumbotron" sets apart header from the body of the webpage

Ctrl+Shift+i-> Mobile View on Top-left gives the responsive mobile view of the webpage (Debugging)

"list-unstyled" -> remove the bullets from <ul> tagged list

Installation for Icon Fonts:-

npm install font-awesome@4.7.0 --save

npm install bootstrap-social@5.1.1 --save 

How to install and use CSS-preprocessors
1. less

npm install -g less@2.7.2

lessc styles.less styles.css


