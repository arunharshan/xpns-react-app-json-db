# Fake API Json-server to deploy into Heroku

### git clone https://github.com/arunharshan/xpns-react-app-json-db.git
1.Modify the db.json file <br/>
2. In the react app modify the API server url once after this file is deployed into Heroku. <br/>
3. env.proccess = 'production' || LOCAL_PORT

### Deploy the code in Heroku
Once the code is in the git repository.<br/>
Got to your Heroku dashboard, connect this git repo by providing the app name ( here it is xpns-react-app-json-db ), then deploy<br/>
#### Demo URL: https://react-json-server-db.herokuapp.com/


### Note:
During the development process, the json-server db.json file is stored locally and the data API calls inside the react is made using concurrently library. 
<br/>
For Heroku deployment process, we need to separate the React APP and Database.
<br/>

### How to deploy the React App 
