# App Path

This is a proof of concept electron app.  It is designed to one thing and that is to display the contents of app.getAppPath().  Any changes should be made to files in the src directory if possible.  

# Quick start

The contents of app/app.js and app/background.js are overwritten when running a build.  Changes to these files should be made to the copies under the src folder to avoid this.  

In order to make changes do the following

```
git clone https://github.com/enxoco/getAppPath.git
cd getAppPath
npm install
npm start
```

# Packages

The Mac installer and app are under the dist folder and also listed under the releases for this repo.  This code is based on the boilerplate in the following repo:

https://github.com/szwacz/electron-boilerplate.git
