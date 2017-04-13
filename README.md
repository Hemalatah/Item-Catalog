# Item-Catalog
  Restaurant menu application built using Python, Flask and SQLAlchemy. This App is integrated with third party user registration and authentication.
Installation needed:
  - Virtual Box
  - Vagrant Machine  
> Guide for installation goes [here](https://www.google.com/url?q=https://www.udacity.com/wiki/ud197/install-vagrant&sa=D&ust=1490854878829000&usg=AFQjCNFHekjbFdZ6IjFikEkXl0kKS2jfXg).
- Now, fork and clone the [fullstack-nanodegree-vm repo](https://www.google.com/url?q=http://github.com/udacity/fullstack-nanodegree-vm&sa=D&ust=1490854878831000&usg=AFQjCNFLyYQ_rt2ifBZCxIdJK3XN7CpLzg) to your local machine.
# Using the Vagrant Virtual Machine

  - The Vagrant VM has PostgreSQL installed and configured, as well as the psql command line interface (CLI), so that you don't have to install or configure them on your local machine.
  - To use the Vagrant virtual machine, navigate to the full-stack-nanodegree-vm in the terminal, create the oauth directory and clone this repo into it. Then use the command vagrant up (powers on the virtual machine) followed by vagrant ssh (logs into the virtual machine).
  - Remember, once you have executed the vagrant ssh command, you will want to cd /vagrant to change directory in order to work on your project, once your cd /vagrant, if you type ls on the command line, you'll see your oauth folder.
  - You'll need to have your vagrant VM up and be logged into it to run your database configuration file (database_setup.py) as below:
  
```sh
$ python database_setup.py
```
- To add the restaurant and menu items into the database:

```sh
$ python lotsofmenus.py
```
- To run the project:
```sh
$ python project.py
```

### Four basic files of the project:

- the HTML (structure of the pages). Here, I used Flask framework to generate the HTML templates
- the CSS (the style of the pages). Here, I used Bootstrap as well.
- the Flask Application (to put it online)
it must include authentication/authorization to allow users to login before making changes. Here, I used google and facebook oauth providers.
- the database (to store and organize the information). Here, I imported SQLAlchemy.


### Running your project!
Once you have your database and python files set up, run the app by typing the url 
```sh
$ localhost:5000
```
in your browser.

> To get the better experience in playing around the application, Try a fresh incognito window for every login and logout inorder to avoid stale cookies and cache to disturb the application.
