React
=====
* A React component is a bit of code that represents a piece of the page. Each component is a JavaScript function that returns a piece of code that represents a piece of a web page.

* React uses a language called JSX that looks like HTML but works inside JavaScript, which HTML usually doesn’t do.

Components : 
  i) Functional - writing components as functions. These are called functional components. // most easier
      Ex: 
      function MyFirstCom() {    
            //functions, variables goes here
            return (      <h1 className="firstText" >I am the child!</h1>    );  
          }
  ii) Class - write components as JavaScript classes. These are called class components. // useful for component state
      Ex: 
      class MyFirstCom extends React.Component {  
             render() {                                       // render function is mendatory for Returing JSX for rendering
                //functions, variables goes here
                return (      <h1 className="firstText" >I am the child!</h1>    );  
             }
          }

** Here  <h1>I am the child!</h1> is JSX

* Class or functional components are rendered by - 
      ReactDOM.render(<MyFirstCom />, document.getElementById('Id'))


Installation: // npm & node.js must be installed
=============
  1. npm install -g create-react-app
  2. npx create-react-app my_project_name
  
Run:
====
  1. npm start

Build:
======
  npm build

Others:
======
   yarn test
    Starts the test runner.

  yarn eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!



