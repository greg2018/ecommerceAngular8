#1) This application modified from the tutorial project:
https://github.com/eugenp/tutorials.git
and cloned in: 
C:\UserAppsFive\baeldungWorkspaces\tutorials\spring-boot-angular-ecommerce
"spring-boot-angular-ecommerce" is the sub project.


Since the "frontend" doesn't work in local environment(mostly due to angular cli comparability problems) , I upgrade this project to Angular 8 version by:
#1.1) Create an angular 8 project
#1.2) copy the source code from the tutorial project to new project

#2) Git respository URL: 
https://github.com/greg2018/ecommerceAngular8.git

#3) To get rid of CORs from server side, use proxy configuration "proxy-conf.json"
 The command is configured in "package.json":
 "start": "ng serve --proxy-config proxy-conf.json",
 When use command line "npm start" it will use proxy(actually execute command line above)  



