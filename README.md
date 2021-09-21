# A project to demonstrate using and extending bootstrap's scss

I have pulled in the scss file from bootstrap.   This is the 'source' code used by bootstrap to generate bootstrap's css.    

The project also has a gulpfile.js that will be used by gulp to process the scss into css.   This also demonstrates using
purge to ship only css used in html.

clone this project local

cd into the project folder

npm i 

if using vscode then use liveserver extenstion to run the dev web server against homepage.html

open console and 'npm run gulp' to get gulp watching your html and scss files.

Try commenting out the purge line in gulpfile.js and have a look at the size of the generated css
