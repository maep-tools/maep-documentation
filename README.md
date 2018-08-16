
<p align="center">
    <img width="460" height="300" src="https://maep-tools.github.io/landing-page/assets/img/theme/Vector.svg">
</p>
MAEP is a collection of tools for electrical engineers for analysis and electrical planning model.  
MAEP web is a tool for manage the models of MAEP.

You can use only the python models for the analysis or if you need this model in your systems.

Maep is a tool written in python 3 and it's very easy to setup.  
You only need a few python libraries and gurobi installed in your computer.
If you need a user interface for understand the model you can install the full solution.


# MAEP Modules

| Modules | Description | Repository |
|--|--|--|
| MAEP  |Models in python for Analysis|https://github.com/maep-tools/model-maep|
| FRONTEND  |User interface of the application|https://github.com/maep-tools/frontend|
| BACKEND  |Backend API build using Laravel for MAEP process management.|https://github.com/maep-tools/backend|

### Installation
To install MAEP it is necessary to have the following technical elements:

- Internet connection (It is necessary to download packages)
- Server ubuntu 16.04 or higher.
- Minimum 512 GB of RAM.
- 2 GB hard drive.

### Screenshots
#### Dashboard
You can see the status of the model in this page. The users can create models in the application only using a web browser.
Is perfect if you are a basic user. 
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/dashboard.png)


#### User management
The administrator can see the users registered in the system. You can configure a lot of roles.
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/users.png)


#### Excel Upload
You can upload the inputs of MAEP from the UI and the system send you a email when the process finish.
![Excel](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/excel.png)


#### User Interface for learn the inputs of MAEP
We design a custom user interface for learn how to use MAEP
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/demand.png)


#### Email notification
The system send a notification to the user email address when the model is processed.
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/email.png)

#### Queue system
You can close the window. And the model will finish in the background.
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/loading.png)

#### Input Validation Screen
You can see if your model is ready to run.
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/validation.png)

### MAEP Sponsors
We would like to extend our thanks to the following sponsors for helping fund on-going MAEP development. If you are interested in becoming a sponsor, please get in touch.

-   Universidad de los Andes
-   Universidad del Rosario
-   Cornell University
-   ISAGEN
-   CEIBA


### Future Work
-   internationalize
-   Improve docs
-   Optimize models
-   Add tests cases


License
----
MIT
Copyright 2018 MAEP

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

