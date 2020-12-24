# FAA NOTAM Developer Portal UI Prototype
## Install APP
Go to the directory of the APP folder `FAA`, open the Terminal and type in the commands below.

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

## Test User Accounts
The APP automatically generates 1 admin account and 5 user accounts for testing.

You can click the `LOGIN` button on top-right of the APP UI to login with these test accounts. Or your can click the `REGISTER` button to create your new account.

There are two types of users in the app: admin and regular user.

##### TEST ADMIN ACCOUNT:
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

## Use The APP
### For admin user accounts
- Home(Dashboard): 
    - Get an overviw of users, keys and requests status
    - Quick manipulation with access keys and requests.
- API:
  - NOTAM API: 
    - View the API Details
  - API Management: 
    - Publish/Unpublish API
    - View & edit basic details
    - Manage access keys, manage log history
    - Update API information  
- SDK:
  - NOTAM SDK:
    - View the SDK feature
  - SDK Management: 
    - Publish/Unpublish SDK
    - View & edit basic details
    - Add & delete SDKs
    - Manage access keys,update SDK information   
- Documentation & Help: 
  - View the help documentation
- User Management:
  - Admin Users: 
    - View user information
    - click row can view details of the selected user
  - Existing Users: 
    - View user access key information.
    - click row can manage the access keys (change key status or delete key) of the selected user.
  - New requests: 
    - View new requests, approve & reject requests. 
    - When approve a request the app will generate a new active access key for the corresponding user.
    - After approve or reject, the request will disappear from the new requests page.
- Statistics:
  - Get statistics charts for API Usage & Requests feature.
- Support:
  - View & Create queries. 

### For user accounts
- Home(Dashboard): 
    - Get an overviw of current user's information, keys and requests status
    - Manage keys
    - Make requests by click `Generate new key` on key management board
    - Get notifications when requests have been dealed with.
- API:
  - View the API Details
- SDK:
   - View the SDK feature
- Documentation & Help: 
  - View the help documentation
- Support:
  - View & Create queries.
  
### For non logged users
- Home: 
    - Get an overviw of API, SDK, Documentation introduction
- API:
  - View the API Details
- SDK:
   - View the SDK feature
- Documentation & Help: 
  - View the help documentation
- Support:
  - View & Create queries.
- Register
  - Create new accounts
- Login
  - Login with existing accounts
