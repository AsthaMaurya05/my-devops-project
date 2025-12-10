\# 🚀 My DevOps Project – Maven + Git + GitHub Actions CI



This project demonstrates the \*\*core DevOps concepts\*\* including  

Git workflow, Maven build lifecycle, GitHub Actions CI pipeline, and version control best practices.



---



\## ✔️ CI Pipeline Status



!\[Maven CI](https://github.com/AsthaMaurya05/my-devops-project/actions/workflows/maven.yml/badge.svg)



---



\## 📌 Project Overview



This is a simple \*\*Java Maven project\*\* generated using the  

\*\*Maven Quickstart Archetype\*\*, and integrated with \*\*GitHub Actions CI pipeline\*\*.



The goal of this project is to demonstrate:



\- Git basics  

\- Branching \& merging  

\- Rebasing  

\- Stashing  

\- Tagging  

\- Maven build \& test  

\- Automated CI pipeline using GitHub Actions  



This project aligns perfectly with the DevOps syllabus topics.



---



\## 🛠️ Tools \& Technologies Used



| Tool | Purpose |

|------|---------|

| \*\*Git\*\* | Version control |

| \*\*GitHub\*\* | Remote repository |

| \*\*Maven\*\* | Build automation |

| \*\*Java (JDK 17)\*\* | Programming |

| \*\*GitHub Actions\*\* | Continuous Integration |

| \*\*Windows CMD\*\* | Git + Maven commands |



---



\## 🔥 DevOps Concepts Implemented



\### \*\*1️⃣ Git Version Control\*\*

\- `git init`  

\- `git add`, `commit`, `push`, `pull`  

\- Connected local repo to GitHub



\### \*\*2️⃣ Branching Workflow\*\*

\- Created branch `feature-message-update`  

\- Updated App.java  

\- Merged back into `main`  



\### \*\*3️⃣ Git Stash\*\*

Used `git stash` to temporarily store changes.



\### \*\*4️⃣ Git Rebase\*\*

Created `feature-rebase-demo` branch and rebased it onto `main`.



\### \*\*5️⃣ Git Tags\*\*

Created release tag:

git tag v1.0

git push origin v1.0





\### \*\*6️⃣ Ignoring Build Files\*\*

Added `.gitignore` to ignore:

target/





---



\## 🧱 Maven Setup



To build the project locally:



```bash

mvn compile

To run tests:

mvn test

Maven automatically downloads dependencies and runs JUnit tests.



⚙️ GitHub Actions CI Pipeline



The CI workflow runs automatically on every:



Push to main



Pull request to main



CI Pipeline Steps:



Checkout repository



Install Java 17



Run Maven tests



Ensure build stability



Workflow file:



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





