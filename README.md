# AirBnB clone_v2: MySQL, deploy web static, web framework

![hbnb](https://camo.githubusercontent.com/a0c52a69dc410e983b8c63fa4aa57e83cb4157cd/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f696e7472616e65742d70726f6a656374732d66696c65732f686f6c626572746f6e7363686f6f6c2d6869676865722d6c6576656c5f70726f6772616d6d696e672b2f3236332f4842544e2d68626e622d46696e616c2e706e67)

## Table of Contents

* [Description](#description)
* [Purpose](#purpose)
* [Requirements](#requirements)
* [File Structure](#file-structure)
* [Usage](#usage)
* [Examples](#examples)
* [Bugs](#bugs)
* [Authors](#authors)
* [License](#license)

## Description

**hbnb** is a full-stack clone of the web application [AirBnB](https://www.airbnb.com/). This clone was built in four iterative phases. This version includes completion of Phase 1 from [AirBnB_clone_v1: Console and web static](https://github.com/bchen528/AirBnB_clone_v1) plus Phase 2, which has three parts: 1) adding a MySQL database storage system and mapping models to a database table using object relational mapping, 2) deploying web static by creating and configuring a web server, and 3) converting static HTML page into a dynamic HTML page using Flask and Jinja2.

### Part 1: Add a MySQL database storage system
![mysql_diagram](https://s3.amazonaws.com/intranet-projects-files/concepts/74/hbnb_step2.png)

### Part 2: Deploy web static with Fabric
![web_static_deployment](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/288/aribnb_diagram_0.jpg?cache=off)

### Part 3: Build a web framework with Flask
![webframwork](https://s3.amazonaws.com/intranet-projects-files/concepts/74/hbnb_step3.png)

**Links to other versions:**
* [AirBnB_clone_v1: Console and web static](https://github.com/bchen528/AirBnB_clone_v1)
* [AirBnB_clone_v3: RESTful API](https://github.com/bchen528/AirBnB_clone_v3)
* [AirBnB_clone_v4: Web dynamic](https://github.com/bchen528/AirBnB_clone_v4) (Final version!)

## Purpose
The purpose of Phase 2 is to learn how to:
* create a MySQL database
* use ORM
* map a Python class to a MySQL table
* handle 2 different storage engines in same codebase
* use environmental variables
* deploy code on a server
* use Fabric for executing local or remote shell commands, uploading/downloading files, prompting the running user for input, or aborting execution. Fabric is taking care of all network connections (SSH, SCP etc.): it's an easy tool for transferring files and executing commands from local to a remote server.
* manage Nginx configurations
* build a web framework with Flask
* define routes in Flask
* create HTML response in Flask using a template
* create dynamic template with Jinja2
* display data from MySQL database in HTML

## File Descriptions
  Note: Below highlights only new file additions for Phase 2. For Phase 1 file descriptions, click [here](https://github.com/bchen528/AirBnB_clone_v1).
  

  
  
