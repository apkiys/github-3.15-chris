# Assignment Answers to CE 3.15

## Create GitHub Repository
01. Create new public git repository with README.md and gitignore.
	gh repo create build_repo --public --description 'description here' --add-readme
02. Git clone repository into local.
	git clone git@github.com:username/build_repo
03. Change path into repository locally.

## Deploy Serverless application
04. Run "npm init".
05. Run "code ." to open the repository directory in VSCode.
06. Create a index.js file and input and save the relevant code.
07. Create a parameter value at the parameter store on AWS.
08. Exit and go back to terminal to run "npm install serverless".
09. Run "npm install serverless-offline --save-dev".
10. Create a serverless.yml file and input and save the relevant code.
11. Run "serverless deploy" to deploy serverless application to AWS.
12. Run "serverless remove" after deployment finish to remove items in AWS.

## Create CI/CD pipeline
13. Add "node_modules" and ".serverless" into .gitignore file.
14. **Create "main.yml" with package scan part and input and save the relevant code in ".github/workflows"**.
15. Run "npm install jest --save-dev".
16. Create a index.test.js file and input and save the relevant code.
17. Change the "test" to include "jest" in package.json file.
18. Run "npm run test" to test the CI/CD pipeline.

## Deploy CI/CD pipeline into GitHub Actions
19. Add "AWS_ACCESS_KEY_ID" and "AWS_SECRET_ACCESS_KEY" to GitHub secrets.
20. Add, commit and push the local repository to remote repository GitHub.
21. Go to GitHub Actions to observe the deployment status.
22. Remove/delete/terminate all AWS service/resources that were created.

https://github.com/apkiys/github-3.15-chris

## Logging with AWS CloudWatch
23. Access CloudWatch Log Groups to see the logs.
![image](https://github.com/apkiys/github-3.15-chris/assets/20112494/009cb885-f734-41e9-a909-c646dc02b525)


