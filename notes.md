package.json ----> hold dependencies; most of them are going on behind the scenes.

Why is React all about "Components"? ---> EVERY UI IS MADE UP OF MULTIPLE BUILDING BLOCKS (=COMPONENTS) HENCE IT MAKES SENSE TO THINK ABOUT USEER INTERFACES AS "COMBINDATIONS OF COMPONENTS" = "Components" are really just a way of thinking about user interfaces. React embraces that concept and gives you tools to build components that you can then combine.

A component tree has one root component that's mounted into a DOM node. You build a tree by nesting components into each other - just as you build a HTML tree when building a standard HTML document.

How do you pass data between components? ---> You build your own "HTML elements" in the end, hence you can also define your own attributes (called "props" in React's world)

How can you output dynamic data in React components (i.e. in the returned JSX code)? ---->You can't put block statements (e.g. if statements) between those curly braces but you can output any result of any JS expression by using this special feature.

Which kind of code do you write when using React.js? ---->DECLARATIVE JAVASCRIPT CODE = With React.js, you define the "goal" (i.e. what should be shown on the screen) and let React figure out how to get there.

What is "JSX"? ----> NON-STANDARD SYNTAX WHICH IS ENABLED IN REACT PROJECTS = React projects like the ones we create via "create-react-app" support JSX syntax. It gets compiled to standard JS code behind the scenes. We use JSX because it is easier to read. React is happening under the hood, but you can write a app with React.
EXAMPLE = App.js lines 27-32.

What does "declarative" mean? ----> You define the target "state" (UI) and React figures out which JS commands need to be executed to bring that result to life.

What is a "React Component"? ----> A component is just that: A JS function that typically returns some HTML (or, to be precise: JSX) code which will be shown on the screen when that component is used.

How many custom React components must a React app have? ----> AS MANY AS YOU WANT!

--- User Interaction & State - Section 45 ---
-- Section 46 - Listening to Events & Working with Event Handlers ----

EVENT LISTENER -- all these event handler props, want a function
as a value, a function passed as a value for **onClick** (ExpensesItem.js <button>) and all these other on props
which then is executed when that event occurs.

-- Section 47 - How Component Functions Are Executed -----
