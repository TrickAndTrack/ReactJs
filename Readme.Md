
# React Js

React is all about components.

### React & components

JSX stand for JavaScript XML

### How React work?
We ultimately built our own custom HTML elements & React is all about components.
we built those components and a componentis basically just a custom HTML elements.

> App.js is special kind of components, it will be our so-called, root Component.

- Organize our soruce code in components folder
- Common convention in react application to name it like this Starting with captila character in one word where if you coombin multiple words in one word so every sub word starts with new Capital character 
> a) Expense.js b)ExpernseItem.js 

## We build A Component Tree
```
<App/> ------><Tasks/>
   |         <Task/> <Task/><Task/>
<Header/>       
```
-app.js rendered into single HTMl page


# props

props simply stands for propertites.


## Question

#### Question 1 Why Components ?

Answer 
- Reusability {Don't repeat yourself}
- Sepration of concearn {Don't do too many things in one and same place (function)} 
> split big chunks of code into multiple smalller function] 


#### Question 2 How is A Components build ? or how a exactly Components build?

Answer a) Combination of HTML CSS & JavaScript

#### Question 3 How is A Components written in react?
Answer
- It's just s function 
- A Component in react is just  a JavaScript function.
```
  function App() {
  return (
    <div className="App">
     
    </div>
  );
}

export default App;
```
