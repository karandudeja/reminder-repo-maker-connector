# reminder-repo-maker-connector

Steps to remember, so that making a repository in my system, need not take a heavy load on the memorisation, but becomes it bit easier, with such gentle reminders and personal notes.

Because sometimes, I am testing things out and my state of mind does not want to be blocked with the old questions - 'how to create a fresh repo on github, synced with local folder?'

## Repo made first on GitHub
- Make a new repo, public/private, WITH initializing a readme file
- Go to the folder on the computer(local folder) inside which, I would like to clone this repo of Github, as a new folder with the same name as on the GitHub repo.
- 'cd' to that folder in the Terminal
- Go to the now newly created repo page, on GitHub
- Use the 'Code' green button with a dropdown
- Select the first 'https' option
- Copy the url text there, i.e. 'https://...', to my clipboard
- Go to Terminal app
- Type 'git clone' and paste the url
- Check the parent folder in the Finder, (in the local folders)
- Find the new folder created for the repo with the readme file, from Github. This folder is now synced with git and GitHub
- Congratulations 🎉

## Repo made first on My Computer
- Make a new repo, public/private, WITHOUT initializing a readme file. [scdl]
  * scdl = step can be done later also
- The above step will create a new page with some instructions, and I need to use the 2nd Option with this bold-text "…or push an existing repository from the command line"
- Go to the folder on the computer(local folder) inside which, I would like to create a project, with a repository that will then be sent(synced) to Github
- Type 'mkdir some-dolfer-name' to create the folder
- Next 'cd' to that newly created folder
- Now inside that folder, in the Terminal, do a 'git init'
- Now do a 'touch textfile.txt'
- Open the text file, write some text and save it
- Go back to Terminal
- do a 'git status', 'git add .', 'git status', 'git commit -m "first commit, with a new text file"'
- Go back to Github
- Copy the text that say 'git remote add origin https://github.com/karandudeja/the-new-repo-name.git'
  * Through this approach, The repo name on GitHub and Local Folder repo can be different
- In Terminal, paste it
- Go back to Github
- Copy the text saying "git branch -M main"
- In Terminal, paste it
- Go back to Github
- Copy the text saying "git push -u origin main"
- In Terminal, paste it
- Go back to Github, and refresh the page
- Congratulations 🎉
