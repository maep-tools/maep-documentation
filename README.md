
<p align="center">
    <img width="86.5" height="113.7" src="https://maep-tools.github.io/interface-landingpage/assets/img/theme/Recurso 16@2x-8.png">
</p>

MAEP is a collection of tools for operation planning of power systems.  
MAEP web interface is a tool for manage the optimization models of MAEP. This tool is an open-source application of free access through a web environment.

### Model
Operation planning model to the operation of hydro-thermal power systems.


MAEP is a collection of tools for electrical engineers for analysis and electrical planning models. MAEP is a tool written in python 3 and it's very easy to setup.  You only need a few python libraries and gurobi installed in your computer.

If you need a user interface for understand the model you can install the full solution.
In this document you can see the screenshots of the UI.


# MAEP Modules

### Installation

| Modules | Description | Repository |
|--|--|--|
| MAEP  |Models in python for Analysis|https://github.com/maep-tools/model-maep|
| FRONTEND  |User interface of the interface application.|https://github.com/maep-tools/frontend|
| BACKEND  |Backend API for MAEP process management.|https://github.com/maep-tools/backend|

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

hundreds of configuration variables categorized.
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/form.png)


#### Email notification
The system send a notification to the user email address when the model is processed.
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/email.png)

#### Queue system
You can close the window. And the model will finish in the background.
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/loading.png)

Check your email address later.
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/queue1.png)

#### Input Validation Screen
You can see if your model is ready to run.
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/validation.png)

#### Results
You can configure the results page. Maybe you want to see a list of charts.
![Results1](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/results.png)

Maybe you only need serve the output. 
![Results2](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/results2.png)

#### Administration

The admin can see the status of all models.
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/admin.png)

The admin can see all models and monitor the system
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/logs.png)

#### Privileges
The admin can config the privileges of the users.
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/privileges.png)

#### Hierarchy editor
The admin can customize the web application hierarchy.
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/categories.png)


#### Security
The modules of your team and your information is protected.
![Dashboard](https://raw.githubusercontent.com/maep-tools/maep-documentation/master/screenshots/login.png)

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


### License
----
MIT
Copyright 2018 MAEP

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

