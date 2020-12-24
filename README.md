# FAA NOTAM Developer Portal UI Prototype
### Install APP
1. Install basic packages
```
npm install
```
2. Install Chart.js to enable charts view
```
sudo npm install -g @angular/cli
npm install @angular/cdk --save
npm install chart.js --save
npm install -g json-server
```
3. Run APP
```
ng serve --port 4200
```
Then open your browser on http://120.0.0.1:4200/ you can use the app. Suggest use Chrome to get better view.

### Test User Accounts
The APP automatically generates 1 admin account and 5 user accounts for testing.

You can click the `LOGIN` button on top-right of the APP UI to login with these test accounts. Or your can click the `REGISTER` button to create your new account.

There are two types of users in the app: admin and regular user.

##### TEST ADMIN ACCOUNTS:
- email: admin@faa.com
- password: admin

##### TEST USER ACCOUNTS:
- email: user1@faa.com
- password: user
- email: user2@faa.com
- password: user
- email: user3@faa.com
- password: user
- email: user4@faa.com
- password: user
- email: user5@faa.com
- password: user
