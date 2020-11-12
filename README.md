# node-express

The steps to setting up a Node.js as file are the following

First, create a repository on github and clone it to your local machine

Next, type the following in Terminal

```
npm init
```
or 
```
npm init -y
```

Then create the rest of the following necessary to complete the json.

After that, you're going to touch the necessary files you need in VS Code. Usually index.js and a second js file like myModule.js to export. 

Next, add, commit and push to github.

Now you can define a function in the index.js file and when you console.log it, it will display in the terminal. Or you can type 

```
const { someFunction } = require("./myModule");
```

This will go at the top of your index.js file.
and then type 

```
module.exports = {
    every,
    function,
    you,
    want
}
```
This will go in your second javascript file.

Now when you console.log the second js file's functions in the first js file's tab, it will display in the terminal.

Finally, git add, commit and push.

