# Basic Framework For Front End Vanilla.js Projects

## Preflight Check
1. Run npm install from the framework root folder. This will create the node_modules and install the dependancies found in the package.json file.
```bash
  npm install
```

1. Run development build using the parcel bundler.
```bash
   npx parcel src/index.html
```
or
```
  npm start
```

1. Run production build using the parcel bundler.
```bash
   npx parcel build src/index.html
```
or
```
  npm run build
```


## GIT SETUP
1. .gitignore ignores files mentioned in it so that they are not uploaded to the remote repository.
2. How to set up repo from VS Code:
   1. Click user profile icon
   2. Sign in to synch settings
   3. sign in with github.
   4. Takes you to the browser to sign in and allow github access
   5. Click on hte Source Control Tab
   6. Publish to git. Make sure it is set to Public repo.
3. How to remove repo from github:
   1. Go to github repo
   2. go to settings
   3. scroll to bottom
   4. Click Delete the repo

## If you make a mistake, just remove the .git and delete the repo. :P

show all hidden files to search them.
```bash
  ls -lah
```

look for a file that is .git
```
  .git
```

remove the .git file
```
  rm -rf .git
```
