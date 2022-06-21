# node_sequelize_ultering_ml40643_1st_step
Express/Sequelize tutorial from ultering.com



A fast overview including some basic operation to get the first taste of it.**
**Begin here to start fresh.
It shows the very basic structure to perform your first sequelize task.
The other posts evolves from this one.

Code from:
[USING SEQUELIZE – EXPRESS PROJECT 1: SUPER SIMPLE PROJECT FOR BEGINNERS – 1ST STEP](https://ultering.com/it4us/?p=1953)



## HOW TO - SUPER FAST



1. Make sure that your env has the following installations and versions:
Node: 16.13.1
or Node: 16.X
Package Manager: npm 8.X

2. Install the libs(node_modules):
  npm install --save express express-generator
  npm install --save nodemon
  npm install --save sequelize sequelize-cli
  npm install --save pg pg-hstore
  npm install --save sequelize sequelize-cli dotenv
  npm install --save serve-favicon
  npm audit fix --force

  **IMPORTANT**

  Notice that the flag has double hyphen (without space) and not simple althogh when copying comes to just one:
  npm instal  - - 
  WRONG: npm instal -

3. Create your local database ou use cloud service.
  TIP: ElelephantSQL has free account and it is super easy and fast.
  https://www.elephantsql.com
  Note: you may choose the database. The tutorial uses "rin544".
  if using ElelephantSQL, has no difference the database name. It uses the username.

4. Go to the app root dir and run:
  run.bat

5. Point to:
  http://localhost:3000/

6. Check the output on the console.

7. Check the database using you db client.
  The "user" table was created and it is empty.
  select * from "user";