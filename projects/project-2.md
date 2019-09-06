---
layout: project
type: project
image: images/filedrop.png
title: UH FileDrop
permalink: projects/uh-filedrop
# All dates must be YYYY-MM-DD format!
date: 2019-07-24
labels:
  - Java
  - Spring / Spring Boot
  - AngularJS
  - JUnit
  - Bootstrap 4
  - Thymeleaf
summary: FileDrop is a web application for the University of Hawaii (UH) for UH users to securely send files.
---

<img class="ui medium right floated rounded image" src="../images/filedrop.png">

[FileDrop](https://www.hawaii.edu/filedrop/) is a University of Hawaii (UH) system web application that allows UH users to send files securely. I was tasked with updating the codebase and implement requested features from users. This web app is used by a lot of departments in UH for example: Health Services, Manoa Admissions, Financial Aid, Information Technology Services, and more. When a user uploads files to FileDrop they select how long they want the files to stay on the server, who they are sending the files to, and any comments for the files. After the files are uploaded FileDrop encrypts the files, and then starts a job is started that is set to run that is set to execute in the amount of days the user selected and when that amount of days has passed FileDrop will wipe the files from the server. What I was tasked to do with FileDrop was to start from an almost scratch code base to rebuild FileDrop with newer versions of the technology stack.

The technology used in the production FileDrop is [Spring](https://spring.io/), [Hibernate](https://hibernate.org/orm/), [MySQL](https://www.mysql.com/), [Quartz Scheduler](http://www.quartz-scheduler.org/), [Thymeleaf](https://www.thymeleaf.org/), and [Bootstrap](https://getbootstrap.com/). My job is to use newer versions of Spring, specifically Spring Boot which makes getting a Spring application up and running without all the XML configuration that is involved. I also made use of the frontend framework [AngularJS](https://angularjs.org/) and updated Bootstrap to the latest version, 4. I had to write code for the backend of FileDrop from scratch as the codebase for the production FileDrop used methods that were now deprecated in most recent versions. This app is the second time I have ever used unit testing through the [JUnit](https://junit.org/junit5/) testing framework and after using it extensively I've come to enjoy unit testing as it helps find bugs that I might not be able to find by just using the application. It also uses the code coverage library [Jacoco](https://www.jacoco.org/jacoco/), which shows how much of the codebase is unit tested, I have to make sure all my code is tested and the coverage shows 100%. Taking on this project has taught me a lot of things, such as: unit testing is a very useful tool that saves time and headaches, how enterprise level applications are developed, making sure a new codebase is able to interact with the current database.

Source (still in development): <a href="https://github.com/lukemcd9/uh-filedrop"><i class="large github icon"></i>lukemcd9/uh-filedrop</a>
