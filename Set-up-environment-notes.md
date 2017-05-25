## CONFIG AND SET-UP BEHAVE FRAMEWORK ON WINDOWS 10
### Required
1. install git
[https://git-scm.com/download/win](https://git-scm.com/download/win)
2. install Python 2.7 and pip
[http://matthewhorne.me/how-to-install-python-and-pip-on-windows-10/](http://matthewhorne.me/how-to-install-python-and-pip-on-windows-10/)
3. install Pycharm 4.5 (pls get license by yourself)
[https://confluence.jetbrains.com/display/PYH/Previous+PyCharm+Releases](https://confluence.jetbrains.com/display/PYH/Previous+PyCharm+Releases)
4. Download chromedriver and paste to Python27 folder
[https://sites.google.com/a/chromium.org/chromedriver/downloads](https://sites.google.com/a/chromium.org/chromedriver/downloads)

**Then follow this link to see how to set-up** [https://youtu.be/xQNN6_QqUwc](https://youtu.be/xQNN6_QqUwc)



## WEB APP BUILD AND DEPLOYMENT
### Set-up ## **Opencart** for homeworks of session 3-6. 
Pls refer below link
[https://www.appseconnect.com/how-to-install-opencart-using-xampp/](https://www.appseconnect.com/how-to-install-opencart-using-xampp/)


### Set-up ## **HomeCinema** project for homeworks related to api data prepare/verification

**Required**
* Visual Studio 2015 or 2016
* SQL Server Express edition 2015 or 2016

**Source**
[https://github.com/chsakell/spa-webapi-angularjs](https://github.com/chsakell/spa-webapi-angularjs)

**Installation instructions**
* Build solution to restore packages
* Rebuild solution
* Change the connection strings inside the `HomeCinema.Data/App.config` and `HomeCinema.Web/Web.config` accoarding to your development environment 
* **Open Package Manager Console**
* Select` HomeCinema.Data` as Default project (in package manager console) and run the following commands
   * `add-migration "initial"`
   * `update-database -verbose`
* Run `HomeCinema.Web` application
* Use `username: chsakell, password: homecinema` to login or register a new account