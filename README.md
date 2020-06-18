
![devops-digram-1](https://user-images.githubusercontent.com/48556545/85008821-1fc02000-b17b-11ea-8df6-2d1e71ad1fa8.png)

# Objective :

Setup up an infrastructure such as there are three teams/environemnts :

1. Production
2. Testing
3. Quality Assurance
Production Team will deploy the code first, now there is some work going on in the developement team which is to be deployed on testing environment which will be sent to the production only when the QA team approves it.

# Requirements :

1. Docker
   - Image: httpd
2. Jenkins
   - Github Plugin
3. System with 2gb ram (Recommended)
4. Git and Hooks
5. Github and Github Webhooks
6. ngrok

## Screenshots :
# Git remote add
<img width="455" alt="git22" src="https://user-images.githubusercontent.com/48556545/85008324-74af6680-b17a-11ea-8d3b-714e5cecfd63.PNG">

#testing  page 
<img width="960" alt="htmlpage" src="https://user-images.githubusercontent.com/48556545/85008411-97417f80-b17a-11ea-99c9-6e5f4bd60d54.PNG">



# build job in jenkins
<img width="960" alt="j1" src="https://user-images.githubusercontent.com/48556545/84889786-179eac80-b0b7-11ea-8c0b-1f47f4bcc6c0.PNG">

# staus of history

<img width="960" alt="update" src="https://user-images.githubusercontent.com/48556545/84903814-2fccf680-b0cc-11ea-94a5-6e3344a606ee.PNG">

# creating webhook to push automatically

<img width="960" alt="webhook" src="https://user-images.githubusercontent.com/48556545/84890736-69940200-b0b8-11ea-8085-e5c403463d51.PNG">

# consol output is successful

<img width="960" alt="success" src="https://user-images.githubusercontent.com/48556545/84891133-0191eb80-b0b9-11ea-9d1d-95d52b02318a.PNG">
  # testing  page 
<img width="960" alt="htmlpage" src="https://user-images.githubusercontent.com/48556545/85008411-97417f80-b17a-11ea-99c9-6e5f4bd60d54.PNG">

# build docker image by jenkins
<img width="960" alt="dockerbuild" src="https://user-images.githubusercontent.com/48556545/84903186-65bdab00-b0cb-11ea-83b1-1efbfbe9fbfe.PNG">
