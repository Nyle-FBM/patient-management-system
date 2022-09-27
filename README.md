# WORK IN PROGRESS (WIP)
- I'll get some more concrete steps in once we begin actually working on the project.
- For now, if you want to just explore what's here:

1. Clone this repo.
2. Install node.js if you haven't already.
3. Change directory to this cloned repo in your terminal.
4. Open up a separate terminal instance at this same directory. (2 instances in total)
5. cd into 'server'.
6. run the command: `npm install -g nodemon`
7. In your ide, create a file under 'server' called .env
8. Ask Ruben for the contents of this file. (We can't have it living on github, it has passwords)
9. While in 'server' run the command: `nodemon server`
10. You should see that the server is running and the mongo connection established successfully
11. If you get errors let Ruben know.
12. In your other terminal instance, cd into 'client'
13. Run the command: `npm start`
14. A browser window should pop up with the running react application.
15. Again if any problems, let Ruben know.