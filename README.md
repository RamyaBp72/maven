## Working with Maven

This repository contains the implementation of **Experiment 2** from the DevOps Lab Manual.

## 📌 Experiment Title
Working with Maven: Creating a Maven Project, Understanding the POM File, Dependency Management and Plugins.

## 🎯 Objective
- To understand the basics of Maven.
- To create a Maven project using IntelliJ IDEA.
- To understand the structure of the `pom.xml` file.
- To learn how Maven manages dependencies and plugins.

## 🛠 Tools & Technologies
- Java
- Maven
- IntelliJ IDEA
- Git & GitHub

## 📖 About Maven
Maven is a build automation tool primarily used for Java projects.  
It simplifies the build process, manages project dependencies, and supports plugins for different tasks.

### Key Features
- **Dependency Management** – Automatically downloads required libraries.
- **Build Automation** – Compiles code, runs tests, and packages applications.
- **Standard Project Structure** – Provides a consistent project layout.
- **Plugin Support** – Allows integration with tools for testing, packaging, and deployment.

## 📂 Maven Project Structure

## ⚙ Steps to Create a Maven Project

1. Install Maven from the official website.
2. Configure environment variables (`MAVEN_HOME`).
3. Open IntelliJ IDEA.
4. Click **File → New → Project**.
5. Select **Maven** as the project type.
6. Configure project details.
7. Create and edit the `pom.xml` file.

## 📄 Example pom.xml
```xml
<project xmlns="http://maven.apache.org/POM/4.0.0"
 xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
 xsi:schemaLocation="http://maven.apache.org/POM/4.0.0
 http://maven.apache.org/xsd/maven-4.0.0.xsd">

 <modelVersion>4.0.0</modelVersion>

 <groupId>com.example</groupId>
 <artifactId>demo-project</artifactId>
 <version>1.0.0</version>

</project>
