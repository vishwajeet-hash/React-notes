# React-notes

<p>
  components in react are basically javascript object that are converted to html nodes by using react dom library which we import in html using script tag

jsx is an html like syntax which we can basically use instead of calling react.createelement everytime to make a component

bt the problem is that browser doesnt understand the jsx code and it also dosent understand the import statements

BABEL compiles your jsx code into pure javascript code that the browser understands.
It can also convert our es6,es5 code which the browser dosent understand to the code that browser understands.
Nesting elements would have been hectic without babel.

WEBPACK is a tool that we have got to resolve our problem regarding browser not
understanding import statements.
It also acts as a bundler that bundles all your js file into a single bundle.js 
file which you can then add in html using script tag
So basically you wont have to worry about arranging the components in order.
if yu would visit its website "https://webpack.js.org/" you can find that it converts all your js,sass nd other files into one js one css one png nd one jpg file

Now you must be thinking that configuring these tools would be a tedious task but dont worry facebook has got our back!
Facebook has created a tool "create react app" using that tool we can setup everything in seconds. 
-------------------------------------------------------------
FOlDER STRUCTURE:
node modules-all the 3rd party packages goes here whenever we install something from npm...
whatever we import which isnt a file path would basically get searched in our nodemodules

in public folder theres this index.html ....
Since we are building a silglepageapplication(SPA) this is that single page
and we dont hve to touch it cra will control it for us .
All we can do is making some small changes like adding some font in the head tag or some css nd script files can be added 
also most importantly we can notice a div named root there which would render our react app
</p>
