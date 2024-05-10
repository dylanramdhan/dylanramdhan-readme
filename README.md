   Webpage: [Personal Website](https://dylanramdhan.github.io/dylanramdhan/)

  ***** Git Commits ******
    - Change into working directory:            cd (WORKING-DIRECTORY)
    - CHECK Git Status:                         git status
    - INITIALIZE Git:                           git init
   
    - ADD file to Git:                          git add <file-name> 
                                       -- OR -- git add . <adds-all-changes-from-current-file>
   
    - COMMIT w/ Comments:                       git commit -m "<commmit-message>"
        - COMMIT w/o Comments:                  git commit --allow-empty-message -m ""

    - PUSH Files TO Repository:                 git push
    - PULL Files FROM Repository:               git pull
        - CHECK Status again:                          git status

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
