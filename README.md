# 🌸 Soul of Bangladesh
<p align="center">
  <img src="https://github.com/13Labonno/SoulOFBangladesh/blob/main/resources/AllPictures/HomePage.png" alt="Soul of Bangladesh Banner" width="600" height="400">
</p>




## Team Name: Soul of Bangladesh Devs

Developed by students of **Information and Communication Engineering,BUP**, focusing on showcasing Bangladesh’s rich culture, heritage, and history through interactive web design.

## Team Members:

1. **MST. Labonno Rahman Oishy** – 2254901107 
2. **Ameer Sohail Aurnab** – 2254901011 
3. **Rabeya Islam Rima** – 2254901055 
4. **Sunehra Tabassum** –2254901047  
5. **Nasrat Jahan** – 2254901061 

# How to Use
## 1. Clone the project
- Install git bash
- Open your local directory's git bash terminal
- Configure git:
    
  `git config --global user.name <github_username>`
  
  `git config --global user.email <github_email>`
    
- Run command:
  `git clone https://github.com/13Labonno/SoulOFBangladesh.git`

## 2. Navigate to the project directory commands
- Navigate:
  `cd SoulOFBangladesh`
- Open VS Code:
  `code .`
- Open terminal:
  `Ctrl + J`
  
## 3. Run the Project on XAMPP:
- Copy the project folder to your htdocs directory:
`C:\xampp\htdocs\SoulOFBangladesh`

 Start Apache and MySQL from the XAMPP Control Panel.
  


  If XAMPP is not found, install from this link:
  `https://www.apachefriends.org/download.html?xampp-win32-1.6.6a-installer.exe`
  
-Open phpMyAdmin, create a new database named bd, and import:
  `/database/bd.sql`
-Open your browser and visit:
  `http://localhost/SoulOFBangladesh/mainPage.html `


# How to Develop
## 1. Create a new branch:
- Run command:
  `git checkout -b <new_branch_name>`


## 3. Commit and Push Changes:
- Commit changes to the local repository:
  
  `git add .`

  `git commit -m "Description of changes made"`

- Push changes to the remote repository:
  `git push origin <new_branch_name>`

## 4. Check CI:
- Go to Github Actions
- Click on a pipeline
- Click on test

## 5. Create a Pull Request:
- Create a Pull Request from new branch to the main development branch.


## 6. Review and Merge:
- Collaborators will review changes in the Pull Request.
- If approved, merge changes into the main branch.

## 7. Update Local Repository:
- Switch back to the main branch:
  `git checkout main`

- Pull the latest changes from the remote repository:
  `git pull origin main`

- Delete the local feature branch (optional):
  `git branch -d <new_branch_name>`

- Delete the remote feature branch (if merged and no longer needed):
  `git push origin --delete <new_branch_name>`
