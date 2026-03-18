# git_hub-guideline:-  

## proper pull request:  
1️⃣ Create a new branch (never work directly on main)  
git checkout -b feature-name  

Example:  

git checkout -b add-login  

2️⃣ Make your changes and commit  
git add .  
git commit -m "Added login feature"  

3️⃣ Push your branch to GitHub  
git push origin feature-name  

Example:  

git push origin add-login  

4️⃣ Create Pull Request on GitHub  

Go to your repository on GitHub  

You’ll see a button: Compare & pull request  

Click it  
OR
Go to Pull requests → New pull request  

6️⃣ Submit PR

Click:

Create pull request    

git pull origin main  
🔁 Full Workflow Summary  
git pull origin main  
git checkout -b feature-name  
git add .  
git commit -m "your changes"  
git push origin feature-name  



## proper repositries:  
Step-by-Step  
1️⃣ Create repository on GitHub  

Go to GitHub  

Click New repository  

Enter name (e.g. todo-app)  

Click Create repository  

2️⃣ Create project folder in terminal  
mkdir todo-app  
cd todo-app  
3️⃣ Initialize Git  
git init  
4️⃣ Create files  
touch README.md app.js .gitignore  
5️⃣ Add code (optional)  

Open files and write your project code.  

6️⃣ Add files to Git  
git add .  
7️⃣ Commit your project  
git commit -m "Initial commit"  
8️⃣ Connect to GitHub repo  

Copy URL from GitHub and run:  
  
git remote add origin https://github.com/username/todo-app.git  
9️⃣ Push your project  
git branch -M main  
git push -u origin main  
✅ Done!  

Now your repository is:

Created

Organized  

⚡ Full Command (Quick Version)  
mkdir todo-app  
cd todo-app   
git init  
touch README.md app.js .gitignore  
git add .  
git commit -m "Initial commit"  
git remote add origin https://github.com/username/todo-app.git  
git branch -M main  
git push -u origin main  

## step no 3:  
we wll add file "git add ."  

## step no 4:  
we'll coomit like send message "git commit -m "message" "  

## step no 5:  
we ll push the branch "git push origin branch_name"  
