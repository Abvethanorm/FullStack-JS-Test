# Full Stack JavaScript Test

**Description**: Simple MERN stack web application that takes in some JSON data from a database and displays the contents in a table. The user also has the ability to add and remove entries within the table. 

**FrontEnd**: React, TailWindCSS, Axios, Toasify, Cors, Mongoose

**Backend**: ExpressJS, Mongoose, Axios

**Architecture**: I decided to go with a layer based architecture due to the benefits it provides when your codebase begins to scale. Also, it is much easier for other developers to understand the work flow and maintain it.

![My Remote Image](https://i.ibb.co/x5y069V/architecture.png)

***How to run*:**

- ***Starting the backend server**:* Navigate to **root/backend** and first install the dependencies using **npm install**, then run the command: ***npm run server.***
- **Starting the frontend server**: Navigate to **root/frontend** and first install the dependencies using **npm install**, run the command: **npm run start**.

***How to test*:**

- **Backend**: Navigate to **root/backend** and run the command: **npm test**

---

**Features**:

- User is allowed to add a new creditor row in the table.
- User is allowed to remove one or multiple creditor rows at a time.
- When a user is added/removed, a user will recieve either a successful or error toaster notificaiton
