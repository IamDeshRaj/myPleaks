# myPleaks
Latest Angular 9.1.6 app with SSR, PWA and Serverless(AWS Lambda), Ready to use.

This application can directly be used to start a new Angular 9.1 project where Server Side Rendering(SSR), Progressive Web App(PWA) and Serverless(AWS Lambda Only) deployement is required. This application is completely bug free and Ready to use with minimum check Angular version and AWS profile checks. And obviously by renaming the application name as per your need.

Here are the Steps:

1. @angular/cli version should be 9.1.5.
2. Go to myPleaks directory and do npm install.
3. To run on local with SSR use following commands.
  1. Build using  - npm run build:ssr
  2. Run using    - npm run serve:ssr
4. To run application locally without SSR, Simply run npm start. 
5. To deploy application on AWS lambda.
  1. Configure AWS cli and profile on your local machine.
  2. Export/Set your AWS default profile. Depends on your operating system like export AWS_DEFAULT_PROFILE=<aws-profile-name> e.g. export AWS_DEFAULT_PROFILE=leaks
  3. Run this command to deploy Angular app on AWS lambda: npm run build:serverless:deploy
