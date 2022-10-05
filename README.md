# Design System
By Hernan Cersosimo

Step by step instructions. Most of what you'll see here is for MacOS environments.

##Install Git & Heroku CLI
1. Check this page https://devcenter.heroku.com/articles/git#prerequisites-install-git-and-the-heroku-cli
2. Install Heroku CLI by writing this code in the terminal <code>brew tap heroku/brew && brew install heroku</code>. You may need to install brew if you don't have it already. 




##Compiling CSS
1. Install SASS
Go to https://sass-lang.com/install and run this code in your terminal: <code>npm install -g sass</code>. You'll need to install Node.js if you don't have it already.
2. Let SASS watch for any changes and compile the CSS
In the terminal, go to the <code>/css</code> folder and type <code>sass --watch /sass:/public</code>
