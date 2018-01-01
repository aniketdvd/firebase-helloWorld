# About
## Google Cloud Functions...

I've written a google cloud function. This function returns "Hello World" to the browser. 
* Language used - NodeJS

## How to use ???

first of all be ready with : 
   * Firebase-tools
   * nodejs installed

Let your working directory, say 'functions-firecast' be the root.
Then we have the following structure.
     
     functions-firecast
        |---functions
        |    |
        |    |---node_modules  /*you need not to touch this. Can be added to gitignore...*/ 
        |    |---index.js      /*Where we'll be working */
        |    |---package.json
        |
        |--->firebase.json

In this repo, you can view that 'index.js' script and yay! we're almost done.

Now fire up your git terminal and chage current directory to the working one and its the time to deploy.

we type 'firebase deploy' and after its done we get the URL. Paste 
the URL in your browser and yess!!! 'Hello World !!!' ! 
