# BennitWebAppV1

This is essentially the car dashboard example that has been striped down.

## To build locally:
1. clone this repo using git
2. go to the project folder and run npm install
3. Build the UI by running npm run-script postinstall
4. start the application using npm start
5. open a browser to http://localhost:3000
6. 


## To deploy to IMB watson
1. install cloudfoundry CLI tool
2. login to a bluemix account: $ cf api https://api.ng.bluemix.net $ cf login (follow prompts)
3. cf push <appName>
