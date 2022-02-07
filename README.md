How to fork this resume project
===============================

Installing this project
-----------------------

### Prerequisites
1. install [node and npm/npx on your computer](https://nodejs.dev/download/)
2. install a git client (like [Github Desktop](https://desktop.github.com/))
3. create a [github](https://github.com/) account and/or log into github


### Install and start the project
1. fork the starter project: go to <https://github.com/mcuringa/resume/> and click "fork"
2. open your git client and clone the repository from your github account
3. using your computer's terminal/console , navigate to the project home (the place where you cloned the repo)
4. run `npm update` to install all of the needed javascript packages (this might take a little while)
5. run `npm start` -- this should start the local development webserve and launch your browser
6. you should see the starter site here <http://localhost:3000>

### Changing the code
To get started programming, open [Atom](https://atom.io) and then got to
`File-->Open Folder`. Choose the project folder (called `resume`) that you
checked out from github.

When you make changes to the program, it should automatically be updated in the
browser. If there are errors, you will be able to see them in the browser, too.

You might want to start by change the _data_ in the JSON files located in
the `data` directory. You can change these to your own work, education, and skills
and most of the site will change.

Next, look at the .js and .jsx files. `App.js` starts the application, but
most of the code is either in `BasicRez.js` (for the basic version)
or `PrettyRez.js` (along with the code that gets imported) for the version
with the more advanced layout.

To stop the site, you can just open the terminal where you started it and
use the <kbd>ctrl-c</kbd> command (that's the 'control' key and the 'c' key
at the same time -- use 'control' even on a Mac).



Using `npm` scripts
====================

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
