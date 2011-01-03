Overview
========

Sample applications with the customizations I like.

simple-app
==========

Simple java application, with testng as testing framework, UTF-8 encoding for resources files, Java 6 compliance, and jar with dependencies generation for easy deployment.

       mvn package
       java -cp target/simple-app.jar com.jm2dev.App

Use target/simple-app-with-dependencies.jar if you don't want to add required jars into classpath.
