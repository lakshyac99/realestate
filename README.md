# Real Estate Application

## To getting started with this project follow the steps given below.

### Step 1. Cloning this Repo by pasting the bellow command in your terminal.

`git clone https://github.com/lakshyac99/realestate-new.git`

### Step 2. Open `api` folder and create `.env` file in it, and check `.env.example` file.


### Step 3. Open up 3 terminal windows.

`1> In first terminal navigate to api`.

`2> In second terminal navigate to client`.

`3> In third terminal navigate to socket`.

### Step 4. Now to push the prisma model type the below command in 1st terminal.

`npx prisma db push`

### Step 5. Now to start the server type the below command in 1st terminal.

`console-ninja node --env-file .env --watch app.js`

### Step 6. Now to start the react front-end server type the below command in 2nd terminal.

`npm run dev`

### Step 7. Now start the socket.io server in 3rd terminal by typing the below command.

`console-ninja node --watch app.js`

### Step 8. Now visit `http://localhost:5173/`.

