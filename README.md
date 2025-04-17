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
- * Make a new repo, public/private, WITHOUT initializing a readme file.
- Go to the folder on the computer(local folder) inside which, I would like to create a repository, that will then be sent(synced) to Github
- Type 'mkdir some-dolfer-name' to create the folder with that name
