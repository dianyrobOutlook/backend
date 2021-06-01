# Project BackEnd with Postman and Newman by Diana Hernandez
## Workshop project session: BackEnd
### Steps to run tests:
#### 1.Clone this repository
#### 2.Open the terminal and go to the project's folder Backend
#### 3.Once you are in the folder Backend, from the terminal execute the next commands to install the required libraries: 
*    npm install --save-dev newman
*    npm install --save-dev newman-reporter-htmlextra
#### 4.To execute the tests and see the results, from the terminal run the next command:
*    npx newman run 'path/collectionFile.json' -e 'path/envVariablesFile.json'
#### 5.To execute the tests and see the results in an html report, from the terminal run the next command:    
*    npx newman run 'path/collectionFile.json' -e 'path/envVariablesFile.json' -r htmlextra --reporter-htmlextra-export 'path/folderToStoreReport'
#### 6.Look for the report generated in the Reports folder and open the file in a browser to see the execution results
