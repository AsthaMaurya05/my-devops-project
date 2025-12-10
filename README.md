🚀 My DevOps Project – Maven + Git + GitHub Actions CI

This project demonstrates core DevOps concepts including Git workflow, Maven build lifecycle, automated CI pipelines, and GitHub version control best practices.

✔️ CI Pipeline Status

📌 Project Overview

This is a simple Java Maven project generated using the Maven Quickstart Archetype, integrated with a fully automated GitHub Actions CI pipeline.

The goal of this project is to demonstrate:

🔹 Git basics

🔹 Branching & merging

🔹 Rebasing

🔹 Stashing

🔹 Tagging

🔹 Maven build & test lifecycle

🔹 Continuous Integration using GitHub Actions

This project aligns perfectly with the DevOps syllabus and industrial DevOps workflows.

🛠️ Tools & Technologies Used
Tool	Purpose
Git	Version control
GitHub	Remote repository hosting
Maven	Build automation tool
Java (JDK 17)	Programming language
GitHub Actions	Continuous Integration (CI)
Windows CMD	Running Git + Maven commands
🔥 DevOps Concepts Implemented
1️⃣ Git Version Control

git init, add, commit, push, pull

Linked local repo to GitHub

Maintained clean commit history

2️⃣ Branching Workflow

Created branch: feature-message-update

Updated App.java

Merged into main via PR

3️⃣ Git Stash

Used git stash to temporarily store changes during workflow.

4️⃣ Git Rebase

Demonstrated clean history using rebase on branch:
feature-rebase-demo

5️⃣ Git Tags

Created a version release:

git tag v1.0
git push origin v1.0

6️⃣ .gitignore Setup

Ignored build files:

target/

🧱 Maven Setup & Commands
✔️ Compile the project
mvn compile

✔️ Run tests
mvn test


Maven automatically downloads dependencies and executes JUnit tests.

⚙️ GitHub Actions CI Pipeline

The CI pipeline runs automatically on every:

🚀 Push to main

🔄 Pull request to main

CI Pipeline Steps

Checkout repository

Install Java 17

Run Maven tests

Verify build success

Pipeline file location:
.github/workflows/maven.yml

📂 Project Structure
my-devops-project/
│── src/
│   ├── main/java/com/mycompany/app/App.java
│   └── test/java/com/mycompany/app/AppTest.java
│── pom.xml
│── .gitignore
│── .github/workflows/maven.yml
│── README.md

🎯 Conclusion

This project showcases essential DevOps practices such as Git workflows, CI automation, and Maven build management — forming a strong foundation for modern DevOps pipelines.


