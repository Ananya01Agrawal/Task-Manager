#Task Manager : Secured on the cloud


---

### Technologies Used:

#### Frontend:

- ReactJS
- Styling: [ Tailwind CSS, clsx, class-variance-authority, tailwind-merge, tailwindcss-animate ]
- UI: [ shadcn-ui, radix-ui, next-themes, react-hot-toast ]
- Validation: [ Typescript, zod, use-form ]
- Icons: [ lucide-react ]
- axios

#### Backend:

- NodeJS
- ExpressJs
- MongoDb
- mongoose
- bcryptjs
- jsonwebtoken

---
![image](https://github.com/user-attachments/assets/283d78f5-7f12-4c4b-a9ab-92993b71cfe1)
![image](https://github.com/user-attachments/assets/d80424fb-ded9-4d33-ad12-8fa31ad1c354)
![image](https://github.com/user-attachments/assets/c33b9e00-00eb-41d5-9d1c-b9674bee8c21)
![image](https://github.com/user-attachments/assets/abe688d0-6db7-4b9a-a90f-ea821a955c1b)
![image](https://github.com/user-attachments/assets/0a401647-b35f-454a-9e9f-0bda43d5c4b2)
![image](https://github.com/user-attachments/assets/43a8b5f8-e814-4683-8b34-18166c199550)
![image](https://github.com/user-attachments/assets/3844f7c4-daa4-42f2-b023-32bc026f0a3e)








## Getting Started with the Project

- Fork the Repository.
- Clone the Repository to your local Environment.

```js
run `git init` in your project directory
run `git clone Your_Repository_Link` 

- Run `npm run init` cpmmand in the root directory of the project (To install all the dependencies).
- Create a .env file in the "Backend" Folder.

```js
JWT_SIGNATURE = YOUR_JWT_SECRET
MONGO_URI = YOUR_MONGO_DB_URL
FRONTEND_DEV = VITE_APP_URL ` http://localhost/3000 `
FRONTEND = YOUR_FRONTEND_WEBSITE_LINK (after deploying your frontend)

```

- Create a .env file in the "Frontend" Folder.

```js
VITE_HOST = ` http://localhost:BACKEND_PORT `
In Development => ` http://localhost:5000 ` (default:5000)
In Production  => YOUR_BACKEND_WEBSITE_LINK (afer deploying your backend)
```

- Run `npm run dev`

`Your App is live on YOUR_FRONTEND_PORT(3000) and server is running on YOUR_BACKEND_PORT(5000)`

---

### Update App according to you.

### Run the following commands

- Setup:
  - `git branch -M main`
  - `git remote add origin main`
  - `git checkout -m [new_update_branch_name]`
- Update or Add any functionality...
- Add and commit Your changes:
  - `git add .`
  - `git commit -m "YOUR_COMMIT_MESSAGE"`
  - `git push -u origin [new_update_branch_name]`

`You have Updated you Github Repository with these changes`

---

## Deploy the App

- Create an Accout on Vercel.com
- Connect your Github account
- Allow Your Repository access for vercel

### Create Frontend

- On Dashboard click NEW_PROJECT
- Select your repository
- Connect your github repository
- Choose root directory as FRONTEND
- Override output direcory to build.

#### Add details:

```js
Name : YOUR_APP_NAME
Branch : main
Root Directory : Frontend
publish directory : build
```

- click deploy.
- Copy your newly created WEBSITE_URL it will needed in next step.

### Create Backend

- On Dashboard click NEW_PROJECT
- Select your repository
- Connect your github repository
- Choose root directory as BACKEND

```js
Add details:
Name : YOUR_APP_NAME
Branch : main
Root Directory : BACKEND

**** Under Environment **** => create a environment variable

key   : FRONTEND, value : YOUR_FRONTEND_WEBSITE_URL (PASTE YOUR FRONTEND URL HERE),
key   : JWT_SIGNATURE, value : YOUR_JWT_SECRET,
key   : MONGO_URI, value : YOUR_MONGO_DB_URL,
key   : FRONTEND_DEV, value : ` http://localhost:3000 `

```

- click deploy
- Copy your WEBSITE_URL
- Go to dashboard and go to your frontend app
- Under Environment => add enviromnment=> create a environment variable

```js
key: VITE_HOST;
value: YOUR_BACKEND_WEBSITE_URL;
```

---

## Your website is live on your Frontend Website Link.
