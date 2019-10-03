Very first time you use a new computer
--------------------------------------

    git config --global user.name "Brian Avner"
    git config --global user.email "brianavner@gmail.com"

Setting up a new project (repository (repo), folder)
--------------------------------------------------------

    git init

When you want to check which step you are on
-----------------------------------------------

    git status

Three steps comit process
----------------------------

    1) Make saved, tested changes to code (usually completely working)
    2) Add any changed files to the stage
        git add filename.rb
    3) Commit the staged files
        git commit -m "Message that describes exactly what you did"