# CoffeeList
This is a web app for a digital coffee list hosted on an Ipad.

# Installation

* Install the pip requirements as denoted in pip-requirements.txt
* Go into CoffeeList.py and change tehdatabase path. This Webapp was tested with SqLite and Postgresql
* Change the admin password in Line 501
* Change the userList.csv in the static folder as shown in the template
* Standard items wil be created at start. You can change the price and names in the admin panel later.
* At the first run: Go into CoffeeList.py and uncomment line 513 ('build_sample_db()')
* Your App should run on localhost at port 5000
* Remember to set the comment line 513 or the database will be rebuild at every start

![alt tag](https://raw.githubusercontent.com/duscheln/CoffeeList/master/screenshots/1.png)
![alt tag](https://raw.githubusercontent.com/duscheln/CoffeeList/master/screenshots/2.png)
![alt tag](https://raw.githubusercontent.com/duscheln/CoffeeList/master/screenshots/3.png)
