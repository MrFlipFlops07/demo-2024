# one hashtag for main headder

descirption!

## 2 hastags for sub header

real
git add. \\ saves files to git.

1) make a folder locally on pc
2) git clone https://github.com/MrFlipFlops07/demo-2024.git
3) cd demo-2024
4) ### git status
    will show changes
5) ### git add .
    will commit the changes but wont update to cloud git repo
6) ### git commit -m "main header" -m "description box"
7) git push also maybe

## for keygeneration
1) ssh-keygen -t rsa -b 4096 -C "nairsreejith0707@gmail.com"    in command line
2) open the public file in a notepad and copy contents and bla bla
3) open powershell as an admin and-
    Get-Service -Name ssh-agent | Set-Service -StartupType Manual
        >> Get-Service -Name ssh-agent

## for final push
1) "git push origin main"

# LOCAL DEVELOPVEMENT

## BRANCHES 
    type git branch : shows master or main
    * main

### to create new branch
    git checkout -b feature-readme-instrusctions
    now when u type git branch it shows ur in the feature-readme-instrusctions
    * feature-readme-instrusctions
    main

# now when we do normal git add commit push it will update only to the feature branch not master
    when we check out and switch back to main all the altered text dissapears.

### final step:
    after working in github doin the pull stuff go back to vs code:
        -git checkout main
        -git pull
        -git branch -d feature-readme-instrsuctions