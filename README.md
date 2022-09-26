# express-server-template

To recreate this setup on your own, follow these steps in order.  Ideally this is a 5 minute process.  Practice helps.

1. Create your repo on github
1. Clone your repo to your local machine
1. add the config folders BEFORE adding anything else. *
1. `cd` into your new repo (if not already inside).
1. `npm init -y`
1. `npm i eslint express jest supertest dotenv cors` and anything else you might need - I typically don't require until I need.  No need for excess node_modules
1. add scripts to your `package.json` file.  See `notes.txt` from config folder
1. `touch index.js` to create root entry into your app
1. `mkdir src __tests__` to create two necessary directories.  These can be created at the same, notice the are a space delimited. 
1. create any other necessary files as desired, I typically do this once they are needed and not in advanced.  No need to have excess unused files

Notes:
\* to copy config files using the terminal run the command:  `cp -r path-to-class-repo/configs/ path-to-the-repo-you-are-setting-up`

- Example I used in class, while in my 401 folder:  the command was `cp -r seattle-code-javascript-401d48/configs/ express-server-template` Notice the spaces.  Context: This command works because the class repo and my "new" repo are in the same folder.  Windows users, this command will likely add the entire configs folder to your repo.  remove from config folder or use alternate command to copy 

