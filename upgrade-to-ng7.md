https://medium.com/techiediaries-com/angular-6-tutorial-series-jwt-auth-rxjs-6-httpclient-bootstrap-4-material-design-routing-and-f80f29ffcb6d

# Angular CLI depends on Node.js

you need to have Node and NPM — Node 8.9 or higher. install Node.js and NPM 

make sure you have Node.js installed `node -v`
install angular cli first time: `sudo npm install -g @angular/cli`

After installing Angular CLI, you can check the version of the installed CLI:`ng version`


## how to upgrade from ng6 to ng7

if you have ng6, run: `ng update @angular/cli @angular/core`

## other upgrade options if you run into issues with the command above

## In order to update the angular-cli package installed globally in your system, you need to run:
---------------------------------
npm uninstall -g angular-cli
npm cache clean or npm cache verify (if npm > 5)
npm install -g @angular/cli@latest

## Update RxJS (RxJS 6 is deprecated)
---------------------------------
npm install -g rxjs-tslint
npm uninstall rxjs-compat


## Then update the core packages and Cli:
---------------------------------
ng update @angular/cli @angular/core
(Optional: update Node.js to version 10 which is supported in NG7)


npm cache verify (recommended)
npm cache clean (for older npm versions)
npm cache clean --force



npm install -g angular-cli - if its your first time
npm install -g @angular/cli@latest - if u already installed, so for updating

npm upgrade -g @angular/cli
