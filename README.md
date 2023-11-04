# template
This is a Website Template for a React js site with all the standard files to correcly deploy.
Duplicate the files in this folder into a newly made repository

Follow the steps to get it set up, ie git init, add, commit, and push
then do npm install and npm install gh-pages --save-dev.

Check inside package.json and above "name" add a "homepage": "http://{git.username}.github.io/{git.repostiory.name}",

Within scripts make sure "predeploy": "npm run build",
"deploy": "gh-pages -d build", are in them

To get the deployed siteadd, commit, and push these changes, and then use "npm run deploy" and make sure it deploys correctly in Actions 
