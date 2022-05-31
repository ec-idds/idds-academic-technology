# IDDS Academic Technology
Information and policy on setting up programming-oriented assignments for the Integrated Digital & Data Sciences initiative at Emmanuel College, Boston.

By Mark Sherman @marksherman \
Assitant Professor of Computer Science \
Director, Integrated Digital & Data Sciences (IDDS) at Emmanuel College

# 1101 Introduction to Programming
Platform: [Codio](https://www.codio.com/)

Codio Project Template: <https://github.com/ec-idds/codio-p5js-workspace-source>

This template is suitable for import directly into a Codio project. It includes configuration for in-Codio viewing of the project web page, in-editor linting provided by Codio via `jshint`, powerful linting via `eslint`. The jshint solution is configured for es6, and eslint used Mark's [eslint plugin](https://github.com/marksherman/eslint-plugin-p5js).

# 2201 Data Analytics
Platform: [Github Classroom](https://classroom.github.com/)

Tools: [R Studio](https://www.rstudio.com/)

# 2132 Practical Machine Learning
Platform: [Github Classroom](https://classroom.github.com/)

Tools: [VSCode](https://code.visualstudio.com/) and [Docker](https://www.docker.com/get-started)

Most assignments are done through existing web sites, and the assignment simply requires editing a README.md to answer prompts by adding text and images. These assignments do not require the Docker component, as the student does not build or run code, but the Docker environment is avaialble to provide linting, spell-checking and other features.. 

An upcoming assignment may use OpenAI Gym. I have an experimental environment for this on the [Python Playground](https://github.com/IDDS-Programming2/python-playground) repository, on the `openaigym` branch. See Programming II, below.

# Programming II & Introduction to Computer Science
_Course taught in JavaScript and Python to study Imperative, Functional, and Object-Oriented styles of programming._

Platform: [Github Classroom](https://classroom.github.com/)

Tools: [VSCode](https://code.visualstudio.com/) and [Docker](https://www.docker.com/get-started)


🌈 JavaScript/p5.js Project Template: <https://github.com/ec-idds/p5js-vscode-template>

🐍 Python Project Template: <https://github.com/IDDS-Programming2/python-playground>

* `main` branch: general use. Currently Python 3.10. Includes linting in VSCode and basic student instructions.
* `xvnc` branch: adds graphical capabilities to do GUI work. 
  * Open <http://localhost:6080/> to access the virtual desktop (this can be in the VSCode built-in preview or in a separate browser)
  * Click "connect" and the password is `vscode`
  * Run python programs by normal means. Graphical programs will appear on this desktop. 
  * Right-click on the desktop to access the menu, which includes settings to change resolution.
* `openaigym` branch: experimental setup for using [OpenAI Gym](https://www.gymlibrary.ml/) based on the `xvnc` branch.

# General Notes
* For Github Classroom, create a Github organization per course. Re-use the organization in successive offerings of the course. This allows assignments to be easily replicated. 
* Docker Desktop 4.8.2 and 4.6.1 work, however the 4.7 branch does NOT work with VSCode.
  * The interface between VSCode and Docker to start/stop/restart containers is buggy with the 4.7 version of Docker Desktop.
* At time of writing, Visual Studio Code was at Version 1.67.2 on May 31, 2022. 
