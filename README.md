# SPEcial

Inside the Zip file there are 3 folder and 2 excel files 
3 folder contains front-end (spe), backend (spe_backend 2) and Database (SQL)

software requirements (node.js and MySQL)

Limitation
1. It can not generate email due to the SendGrid API is exposed in the github public.
2. Create a MailTrap account Then Change the user and pass in the transporter (inside createSPE.js and scheadule.js) Without doing this it cant generate email for testing the create SPE feature

Steps for running the system
1. Create a connection in MySQL
2. import /SQL/SPEcial.sql file into MySQL
3. Change the connection information inside spe_backend 2/ORM/connection.js (change the user, pass and host)
4. Open terminal or command prompt 
5. navigate to the spe directory
6. type 'npm install'
7. Open another terminal or command prompt
8. navigate to 'spe_backend 2' directory 
9. Type 'npm install'
10. In both terminal or command prompt type 'npm start'
11. You can now Access the system in http://localhost:3000
