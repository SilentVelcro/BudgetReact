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

EVENT LISTENER --(HTML ELEMENT that is an EVENT) all these event handler props, want a function as a value, a function passed as a value for **onClick** (ExpensesItem.js <button>) and all these other on props
which then is executed when that event occurs.

**-- Section 47 - How Component Functions Are Executed -----**
fuctions should always be preformed before **Return**

**-- Section 48 - Working with "State" -----**

State is actually not a React specific concept, but it is a key concept in React.

**useState** - is a fuction that creates a special kind of variable where will make changes will lead
this component function to be called again.; provided by the React library (line 1 of ExpenseItem.js { useState }.) Specific instance, so it can be repeated on a per component instance basis, having seperate states allows only changes to one element. (like the title in each <ExpenseItem />)

    It allows us to define values as STATE where changes to these values should reflect in the component function being called again, which is a key difference. by the fact that they start with the word "use" in their name.

    All these hooks must only be called inside of React component functions. They can't be called outside of component functions. They shouldn't be called in any nested functions. They must be called directly.

     **useState** returns an ARRAY where the first value is the value that is being managed (current state value), and the second element in the array is that updating function. (Array Destructuring happens to store both elements in separate variables or constants). It is managed by React in the memory

     If you have data, which might change, and where changes to that data should be reflected on the user interface then you need state because a regular variables will not do the trick with state.

**-- Section 51 - Adding Form Inputs -----**
**-- Section 52 - Listening to User Input -----**
**-- Section 53 - Working with Multiple States -----**
**-- Section 54 - Using One State Instead (And What's Better) -----**
**-- Section 55 - Updating State That Depends On The Previous State -----**
**-- Section 56 - Handling Form Submission -----**
**-- Section 57 - Adding Two-Way Binding-----** (could look more into)
**-- Section 58 - Child-to-Parent Component Communication(Bottom-up)-----**
**-- Section 59 - Lifting The State Up-----**
