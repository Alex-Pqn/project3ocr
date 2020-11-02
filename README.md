# project3ocr

## Presentation

Name of the project : project3ocr (Project 3, OpenClassrooms)

Author : Alex Pqn

Project status : finished (in devlopment)

Project start date : 16 April 2020

Project end date : 20 May 2020

Quick Description : Project designed and intended to reproduce the models of a site for preparing and assembling food menus.

## Installation

The installation uses npm Node.js. Install it on your I.D.E to take advantage of the "npm" commands in your terminal.

to install "sass".
> npm install sass

- - -
The site must be fully compatible with the latest desktop versions of Chrome, Firefox and Safari.

Two possibilities to interact with the project prefixes !

1. Install an automatic prefixer extension (the default script "prefix" in the package.json is suitable for the extension "autoprefixer" in Visual Studio Code).
You can customize this script if you use another extension in your I.D.E.
Once the script "prefix" customized according to your extension, you can skip step 2 and continue the installation.

2. If you don't want to use an autoprefixer, please add them manually in file at "sass/utils/_prefixes.scss" (create it yourself) and import "_prefixes.scss" into "scss.main" with the syntax already used.
If you choose this method, you can remove the "prefix" script and ignore the rest of the installation, just type "npm run sass" to start the sass script.
- - -

to install "concurrently" (program script to launch scripts "sass" and "prefix" at the same time, possibility to take another).
> npm install concurrently

to run the two scripts with "concurrently" (another command if you have another program script for make this)
> concurrently "npm run sass" "npm run prefix"
