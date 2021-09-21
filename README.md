# A project to demonstrate using and extending bootstrap's scss

I have pulled in the scss file from bootstrap.   This is the 'source' code used by bootstrap to generate bootstrap's css.    

The project also has a gulpfile.js that will be used by gulp to process the scss into css.   This also demonstrates using
purge to ship only css used in project content (html, etc).

clone this project local:

git clone https://github.com/philrwebb/genbootstrap.git

cd genbootstrap

npm i 

if using vscode then use liveserver extension to run the dev web server against homepage.html

open vscode console in the genbootstrap folder and 'npm run gulp' to get gulp watching your html and scss files.

Try commenting out the purge line in gulpfile.js and have a look at the size of the generated css

All of the above assumes you have node installed https://nodejs.org
