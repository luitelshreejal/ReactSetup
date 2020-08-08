# ReactSetup

# Setting up a React Projector!

1.	Open up the terminal and go to the directory where you want the project directory to be inside of. 

2.	Type npx create-react-app my-blog

    a.	The directory that’s created is my-blog.

3.	Navigate to the my-blog and run the localhost

    a.	cd my-blog
    
    b.	npm start

4.	Modify the default code to make it our own! 

    Note that there is the public and src directory. 

    In the public directory, it contains items that create-react-app command put there by default (html and       manifest.json). manifest.json is what’s configured it for mobile devices and html is the default. 

    In the src directory, the bulk of our code will go there. 

    App.js is the root component for the website and App.css is the css that will go with it. 










# Part 2:

    Unlike, CodePen, export default `%{VariableName}` needs to be placed in order to import that file in a different file. To use the "react-router-dom" library npm install react-router-dom. 

    import {
	    BrowserRouter as Route,
	    Route,
    } from “react-router-dom”;

The above helps initialize the paths within the main App.js file. Here is how to do so. 

    <Router>

        <Route path="/" component={`%fileNamePageWillGoTo`} exact />
        <Route path="/about" component={`%fileNamePageWillGoTo`} />
        <Route path="/articles-list" component={`%fileNamePageWillGoTo`} />

   </Router>









