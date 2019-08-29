---
layout: post
title:  OOP Insfructure Setup
date:   2019-08-28 13:07:00 -0500
categories: RiceU
tag: Courses
---

* content
{:toc}


What is this?
====================================

This is for the course COMP 504 Graduate Object-Oriented Programming and Design by Mack Joyner.

I just want to keep track on what I have done on my professional study/life/career/...

Hope this behavior is not against Rice's Honor Code.


Step 1: Java 11 Setup
====================================

We are supposed to use Java 11 for this course. To check my Java version, open Terminal and input:
> java -version

It turns out that my Java version is 8 (1.8.someNumber). So I go to Oracle website to download Java SE Development Kit 11. I am asked to login my Oracle account but login is all wanted, no charging.

The new downloaded JDK is located at:
> /Library/Java/JavaVirtualMachines

What I do next is have my JAVA_HOME and PATH point to the new installation. Open Terminal and input:
> export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk-11.0.4.jdk/Contents/Home

> export PATH=$JAVA_HOME/bin:$PATH

Then check Java version again. 
> jiandembp:~ jianchen$ java -version

> java version "11.0.4" 2019-07-16 LTS

> Java(TM) SE Runtime Environment 18.9 (build 11.0.4+10-LTS)

> Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.4+10-LTS, mixed mode)

Done!

But the problem is that after closing this Terminal window and opening another one and try again, it goes back to version 8. I do not know why but it is solvable by deleting the unwanted JDKs in the JavaVirtualMachines folder. I will not fix it now. I will use this method when it is necessary in the future.


Step 2: Maven Setup
====================================

Maven is a bulid automation tool which simplifies Java development processes, especially dependency management.

I download the Apache Maven file from its website and put it under /Users/jianchen

Then I have MAVEN_HOME and PATH point to the new installation:

> export MAVEN_HOME=/Users/jianchen/apache-maven-3.6.1

> export PATH=$PATH:$MAVEN_HOME/bin

Then I check:

> JiandeMacBook-Pro:~ jianchen$ mvn --version

> Apache Maven 3.6.1 (d66c9c0b3152b2e69ee9bac180bb8fcc8e6af555; 2019-04-04T14:00:29-05:00)

> Maven home: /Users/jianchen/apache-maven-3.6.1

> Java version: 1.8.0_211, vendor: Oracle Corporation, runtime: /Library/Java/JavaVirtualMachines/jdk1.8.0_211.jdk/Contents/Home/jre

> Default locale: en_US, platform encoding: UTF-8

> OS name: "mac os x", version: "10.14.6", arch: "x86_64", family: "mac"

Done!


Step 3: IntelliJ (Ultimate Edition) Installation
====================================

Go to Jetbrains website and register a JetBrains Educational Pack, for free!


Step 4: GitHub Classroom Setup
====================================

Select my netid and connect my GitHub account to the lab classroom.


Step 5: Lab 1 Exercise
====================================

Get into the Git classroom. Ensure the files are available and get ready for the lab!!!

Open IntelliJ. Click "Check out from Version Control" --> "Git" on the welcome screen or under "VCS" menu tab. Input the GitHub classroom url and clone (checkout) (aka download) this repo.

(If using command line instead of INtelliJ, use 
> git --version

> git checkout https://github.com/RiceGradOOCourse/lab1-iamjianchen.git)

Then I find there are there functions to complete so there are three TODO comments. The lab is to output "Hello, World!" on my Chrome browser.

1. //TODO Add the REST get request method to with a "/" endpoint that returns the string "Hello, World!"
   > （Cannot post cuz Rice's Honor Code）

2. //TODO add a redirect from the endpoint "/hello" to "/"
   > （Cannot post cuz Rice's Honor Code）

3. //TODO print out the request method and url
   > （Cannot post cuz Rice's Honor Code）

At last, add, commit and push it to my GitHub classroom cloud repo.











