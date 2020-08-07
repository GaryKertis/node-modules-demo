# Node Modules Demo

## Cues

### JavaScript files on the Browser

### Add script tags to include the nyancat and doge scripts to HTML

### Add a script tag to `console.log` the variables in each of the script files

### Add an index.js file

Emphasize trying to `console.log` the variables in the index.js file and compare to the Browser

### Add `module.exports` to the script files

### Extra: `console.log(module)`

Show that it's an object with a lot of properties

### Create a cool.js file and put a two functions in there and show to export multiple things from one file and in index.js show both ways to grab multiple things to import

### Create package.json and show a simple script

- What is `package.json`?
    - Holds metadata relevant to our project. Serves almost as an entry point and gives information to `npm` to identify the project as well as handle the project's dependencies
- What is `package-lock.json`?
    - Auto generated for when `npm` modifies either `node_modules` or `package.json`
    - It's an exact versioned dependency tree
        - We may use a certain version of something but when we run `npm install`, how can we guarantee that we get the same version?
- What are `node_modules`?
    - Contains libraries downloaded from `npm`
    - Should be in our `.gitignore` (We should not push it to Github)
