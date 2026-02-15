steps:
1) Go to frontend folder and run Command: "npm i -f"   to install all dependencies.
2) Run Command once all dependencies was intall "npm start" to run project.
3) Go to backend folder and run command "npm i" to install all dependencies.
	a) open Compass for mongoDb and make connection with connection string.
	b) once db connected so come in terminal of backend folder and run command: "npm run start:listener" to start listener.
	c) after listener command use another command: "npm run start:emitter".
	d) and now run command : "npm run start:server" to start server. 