# Fake API Json-server to deploy into Heroku

### git clone https://github.com/arunharshan/xpns-react-app-json-db.git
1.Modify the db.json file <br/>
2. In the react app modify the API server url once after this file is deployed into Heroku. <br/>
3. env.proccess = 'production' || LOCAL_PORT


### Note:
During the development process, the json-server db.json file is stored locally and the data API calls are made using concurrently library. 
<br/>
For deployment process, we need to separate the React APP and Database.
<br/>

### How to deploy the React App 
