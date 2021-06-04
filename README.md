## VS Code Productivity

# Download VS Code

https://code.visualstudio.com/download

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

# Minimap

- allows you to scroll quickly through a file
- most folks do not use it and it can be disabled from settings

# Sidebar

- open command palette, toggle side bar position

# Emmet

Emmet allows you to write html faster.
If you want it work with tab

1. open settings
2. search emmet for it's setting.json
3. "emmet.triggerExpansionOnTab": true
   if not you can control emmet with `ctrl space`

# Font Ligatures

- https://github.com/tonsky/FiraCode
- actual font https://github.com/tonsky/FiraCode/tree/master/distr/ttf

1.  install the font
2.  open vs code settings
3.  search for fonts
4.  replace font family with `Fira Code`
5.  edit settings.json for Font Ligatures
6.  "editor.fontLigatures": true

# Peacock Extension

- if you have mutiple instances of vs code open it allows you to color the title bar making it easier to look at
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock
- open palette, type in peacock and choose a color

# Moving code around

1. You don't need to highlight a line to cut or copy
2. You can move a line a code up or down by holding down option
3. An easier way to duplicate lines is `opt + shift + up or down`
4. Quick way to delete lines `cmd + shift + k`
5. You can fold elements that are really long by using the arrow next to code lines

# Navigating Code & Refactor

1. See most recent file `cmd + pp`
2. Symbol broswer: `cmd + p` type @, #, or @:
3. Refactor and rename a variable everywhere: `fn + f2`. You can press `shift + enter` to preview
4.

# Multicursor

1. Get all instances of that word `cmd + shift + L`
2. Highlight one by one each instance `cmd + D`. You can skip instances by using `cmd + k`
3. Place cursor through out document that are not consectuive `press and hold Alt + click`

# Find and Search

1. Find within a file `cmd + f`
2. You can use Regex to search within a file as well ex: input|body
3. You can then use `alt + enter` for multi cursor
4. Global searcg `cmd + shift + f`
5. Find and replace: highlight a word you'd like to replace `cmd + opt + f`. You can replace one instance of all

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

# Things I didn't cover but you should check out

- VS Code Debugger
- Docker
- Remote Managment

# More Extensions

- Tailwind CSS IntelliSense
  - VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss
- vscode-styled-components
  - VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components
- Auto Rename Tag
  - VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag
- Prettier - Code formatter
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
- Simple React Snippets
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=burkeholland.simple-react-snippets

# Resources

Front End Masters
https://frontendmasters.com/courses/customize-vs-code/
