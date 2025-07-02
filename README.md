# Quiz Management System (Java Swing + SQLite)

A simple GUI quiz application written in core Java. 100 % offline, no servers.

## Features
* Add unlimited multiple‑choice questions (admin panel).
* Take quizzes and get instant scores.
* SQLite backend – single portable `quiz.db` file.
* Pure Java Swing UI (no external frameworks).

## Quick Start
```bash
# clone
https://github.com/Ranvijaya13/Quiz-Management-System/edit/main/README.md
cd QuizManagementSystem

# download SQLite driver once
mkdir -p lib && curl -L -o lib/sqlite-jdbc.jar \
     https://repo1.maven.org/maven2/org/xerial/sqlite-jdbc/3.45.2.0/sqlite-jdbc-3.45.2.0.jar

# build & run
code .           # open in VS Code (optional)

# or from terminal
javac -cp "lib/*" -d bin $(find src -name '*.java')
java  -cp "bin:lib/*" com.quizapp.Main

---

## 📝 Next steps
* Open the folder in VS Code → **Run ▶** (it will build & launch thanks to `tasks.json`).
* Use the **Add Question** button first to populate the DB, then choose **Take Quiz**.
* Stage, commit, and push your code to GitHub (see instructions in the chat).
