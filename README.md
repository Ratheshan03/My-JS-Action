# My-JS-Action

My first GitHub Action
- Greets the user on debugger for every pullrequest and commits

## Setup the workflow
- Download [NODEJS](https://nodejs.org/en/)
- Create a Repository
- Clone the Respository
- Install and Create depencies in Root directory 
    - " npm init -y "
    -   create action.yml
          - Add necessary code in action.yml
    - " npm install @actions/core "
    - " npm install @actions/github "
    -   create index.js 
          - Add neccessary code in index.js
- Stage the changes

- Commit the changes 

- Tag the commit 
    - " git tag -a -m "commit - message" v1
   
- Push the changes
    - " git push --follow-tags "

- Create main.yml file 
    -  .github/workflows/main.yml (make sure to add this file location)
    -  Add necessary code and customize it
    -  stage and commit the changes
    -  push the code
 
- Navigate to to your repository 
    - select ACTIONS Tab
    - select the recent workflow
    - Check the debugger console
    
####  HOLA 🥳 !!! You have created your GITHUB Workflow..



- Licensed by [MIT](https://github.com/Ratheshan03/My-JS-Action/blob/main/LICENSE)
