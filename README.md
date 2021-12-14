# NYU_Coins2

To run code locally, do the following:

Download GitHub repository from https://github.com/networks-project/NYU_Coins

Open code editor application, I used Microsoft Visual Studio Code

Install Node.js as well as NPM which should be enabled by default
  In code editor terminal enter: node -v
  In code editor terminal enter: npm -v

Install Vue CLI by entering the following in editor terminal: npm install -g @vue/cli

In the code editor terminal, cd into \my-project directory and enter: npm i axios

Install MongoDB Community Server: https://www.mongodb.com/try/download/community
  This tutorial helps with install: https://youtu.be/FwMwO8pXfq0

In new terminal, cd into \backend directory and enter: npm init -y

Now enter: npm i body-parser cors express mongoose

Close all terminal tabs

In new code editor terminal, first cd into \backend directory, then enter: node app.js
  You should see: Connected to port 4000, Database connected

In new terminal, enter: yarn serve
  Ctrl Click on http://localhost:8080/
  
 IMPORTANT: When entering Crypto abbreviations into the submit box, USE ALL CAPITALIZED LETTERS. If you use lowercase, it won’t be able to be deleted due to a bug
 
The code that we wrote is in the following files:
  /src/App.vue
  /backend/app.js
  /backend/database.js
  /backend/models/Crypto.js
  /backend/routes/crypto.route.js

