## VS Code Productivity

# Download VS Code

https://code.visualstudio.com/download

# Resources

Front End Masters
https://frontendmasters.com/courses/customize-vs-code/

# Tour around VS code
    - left hand side is the activity bar and this opens the side bar
    - bottom bar is called the status bar
    - panel which you can access from `ctrl ``

# Basic hotkeys

1. Intergrated terminal 'ctrl + `'
2. Open a file `cmd + p`
3. Hide sidebar `cmd + b`
4. Open palete `cmd + shift + p`
5. Save `cmd + s`
6. Open Setting `cmd +`

# Themes
    - open the command palette and type theme
    - scroll through the themes
    - you can install additional themes as well

# Icon Themes 
    - open the command palette and type Icon
    - scroll through icon themes

# Workspaces
 - allows you to open more than one project within vs code

# Emmet

1. emmet if you want it work with tab
   somestimes emmet disappears, ctrl space will get it back
   (.item>img)+(.item>div#sam)
   emmet is smart enough that if you specifc a class it will know you want a div
   ul>.list-item\*3
   div#main.body
   "emmet.triggerExpansionOnTab": true

# Font Ligatures


# Multicursor

1. Get all instances of that word `press & hold command + D`
2. Place cursor through out document that are not consectuive `press and hold Alt + click`

# Git WorkFlow

1. git clone
   - `cmd + shift + P` type `git clone`
   - place url in input
   - vs code will then allow you to repo
2. Inline Changes
   - the colored bar on the side shows changes made and you can choose to stage them or revert them
   - up and down arrows indicate moving up and down within the file
3. Activity Bar
   - once you hit save `cmd + s`, you'll see in the activity bar refresh with changes
   - you can open this up with `ctrl + shift + g`
4. git commit
   - stage your changes from here and commit with a message `cmd + enter`
5. git push
   - navigate to the ellipis at the top or you can use a sync. The difference is the sync will pull first and you'll need to address conflict before pushing
6. Undoing last commit
   - if you accidentally commit something, click the ellipis and undo last commit.
7. Create new branch
   - you can create a branch as easy as pressing the branch name on the bottom
8. Github Pull Request Issues
   - VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github
   - you can directly make pull request, comment, merge in to master and more with this extension.
9. Git Lens
   - does inline git blame and adds more features on to pull request extension
   - VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens

# Misc

- opening a repo with vs code by using `code .`
- open the palette, type path, make sure the shell command install code command is installed
