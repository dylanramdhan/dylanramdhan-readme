   Webpage: [Personal Website](https://dylanramdhan.github.io/dylanramdhan/)
   
    Git Commands:
    - Change into working directory:            cd <working-directory>
    - Check Git Status:                         git status
    - Initialize Git Repository:                git init
   
    - Add Files to Git:                         git add <FILE_NAME> 
                                       -- OR -- git add . (adds all changes from current file)
   
    - Commit Files to Git:                      git commit -m "<commmit-message>"
        - COMMIT w/o Comment:                   git commit --allow-empty-message -m ""

    - Add Remote Repository:                    git remote add origin <remote-repository-URL>
    - Push Files to Remote Repository:          git push origin main
    - Pull Files from Remote Repository:        git pull origin main
        - Clone Remote Repository:              git clone <remote-repository-URL>
        - Check again:                          git status

    GitHub Branches:
    - CURRENT Branch:   git checkout
    - CHANGE Branch:    git checkout <branch-name>
    - CREATE Branch:    git checkout -b <branch-name>
    - DELETE Branch:    git branch -d <branch-name>
    - MERGE Branch:     git merge <branch-name>
    - LIST Branches:    git branch
        - LIST Files in Branch: git ls-tree <file-name>
    - PUSH Branch:      git push origin <branch-name>
    - PULL Branch:      git pull origin <branch-name>
    - RENAME Branch:    git branch -m <new-branch-name>
