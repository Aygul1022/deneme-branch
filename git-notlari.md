## What is Git and GitHub
git= versiyon kontrol sistemi
avantajları: Kaydetmek, projeyi developerlarla paylaşmak.

commit = her bir kaydetme
branch = farklı development süreçlerinin aynı anda farklı konumlarda yapılabilmesini sağlayan dallandırma sistemi. Her branch deki her bir commit git ile kaydedilir. Bu sayede farklı bir sürümüne dönülüp development adımları o andan ilerletilebilir.
Repository = Directory that we add git commits of projects

# Commites:

## git terminal commites(git bush) ;
1. ls = Shows files and locations inside of the current folder that we are in

2. pwd = Print working directory

3. cd NAME_OF_DİRECTORY = going inside of folder in current directory.

4. cd .. = Come back to previous folder location

5. clear = Cleans the terminal

6. mkdir NAME_OF_DİRECTORY = Make directory (Generates new folder)

7. touch = creates file

8. touch note(NAME).txt = Create text document

9. rm NAME_OF_FİLE = Remove the file //cannot remove folders

10. rm -rf NAME_OF_DİRECTORY = Can remove folder

11. git = shows git commites

12. git config --global user.name




## git commits
1. git add 
 //from the folder add s to Index-Staging 

2. git commit 
 //commits to local repository

3. git status 
//shows updated version of git

4. git init  
//connects git to current directory

5. git commit -m "DESCRİPTİON"  
//commits changes with a desccription

6. git log  
//shows logs o commits (each commit has h number to use to come back that initial state)

7. git add .
//adds all changes in each file at once 

8. touch .gitignore 
//creates a file for hiding files 

(once you create it you can write name of the files you want to make invisible inside it in editor)

9. git commit -m "Commit mesajı"

10. git pull origin <branch-name> 
//git pull is used to pull the latest changes made by your teammates. This command helps you keep the project up to date by pulling updates from the remote repository to your local machine.

11. git push --set-upstream <Repository URL> <branch-name>
//git push is used to push your local changes to a remote repository. This allows for sharing changes when collaborating with team members.

12. git merge <branch-name>
//git merge is used to incorporate changes made in one branch into another. This is often used to merge a feature branch into the main branch.

13. git checkout main

14. git remote add origin <Repository URL>

15. git branch -m main
//Changing the branch you work in

16. git push -u origin <branch-name>
//Once you done 14 th commit you can do this

17. git commit --amend   
//son commit mesajını değiştirmek için


18. git restore <FİLENAME>  
//staging alanındaki dosyayı geri almak için




