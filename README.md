# BlogSphere — Blog Platform with Comments

Task 4 full-stack internship project based on the supplied task brief.

## Features
- Registration, login and JWT authentication
- Create, edit and delete your own posts
- View and search posts
- Add and delete your own comments
- REST API + MySQL integration
- Responsive React frontend

## Run
1. In MySQL Workbench run `CREATE DATABASE blogsphere_db;`
2. Create `.env` from `.env.example` and enter your own MySQL password.
3. In Command Prompt run `npm install`
4. Terminal 1: `npm run server`
5. Terminal 2: `npm run dev`
6. Open `http://localhost:5173`

Never upload `.env` to GitHub.

## GitHub
```cmd
git init
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git add .
git commit -m "Add BlogSphere full stack blog platform"
git push -u origin main
```
