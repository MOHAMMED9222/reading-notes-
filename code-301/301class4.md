## React Doc

**Controlled Components** in HTML, form elements such as < input > , < textarea >, and < select > typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
React will look at the virtual DOM, it also has a copy of the old virtual DOM, that is why we shouldn't update the state directly, so we can have two different object references in memory, we have the old virtual DOM as well as the new virtual DOM.

How do we target what the user is entering if we have an event handler on an input field?
When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name

## The Conditional (Ternary) Operator Explained

**The Conditional (Ternary)** shortens your if statements into one line of code with the conditional operator.
condition ? value if true : value if false

## things i want to know

