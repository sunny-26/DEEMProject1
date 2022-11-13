# Website of the team "DEEMa"
Course Planspiel Web Engineering WS22/23

## NOTE: this is a project of students from TU Chemnitz, Germany 

How to run locally on Windows:
1) Install latest [Ruby+Devkit](https://rubyinstaller.org/downloads/)
2) Install [Docker Desktop](https://docs.docker.com/desktop/install/windows-install/)
3) Open Docker application.
   1) Click on "Settings gear" (top right).
   2) Select "Resources" -> "File Sharing".
   3) Add here the project folder path.
4) Open WebStorm / Intellij Idea with the project.
5) Navigate to docker-compose.yml file
6) Near the "services" word on the left side there is a green arrow highlighted as "up". Click on it.
7) On the bottom there is now sub-window opens with "Docker-compose: deema" and two sub-points: "build" and "site".
8) Click first on **build** log, check if it launches and then click on **site** launch log.
In case of successfull launch, the last lines of "site" should be like that:
`Server address: http://0.0.0.0:4000//
2022-10-30T00:23:05.697479400Z   Server running... press ctrl-c to stop.`

The website is running under http://localhost:4000.

It updates each time any of the files is changed. Update of the website takes up to 5 seconds.

For precise CSS site copy use **vercel** and not locally launched copy.

**BEFORE PUSH-REQUEST CHECK DESIGN/CONTENT WITH VERCEL.**