*Reading Notes*

# HTML FORMS

*HTML Forms* you to communicate with your end users and provides a method to make the web dynamic. HTML forms handle important functions like taking orders, surveys, user registration and more.

**DESIGNING YOUR FORM**

From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.

**ELEMENTS**

< BUTTON > 
The markup for our form is almost complete; we just need to add a button to allow the user to send, or " submit ", their data once they have filled out the form. 

< LABEL >
For usability and accessibility, we include an explicit label for each form control. Note the use of the for attribute on all < label > elements, which takes as its value the id of the form control with which it is associated — this is how you associate a form control with its label.

< INPUT >
On the <input> element, the most important attribute is the type attribute. This attribute is extremely important because it defines the way the <input> element appears and behaves. 

< TEXTAREA >
The <input> tag is a void element, meaning that it doesn't need a closing tag. <textarea> is not a void element, meaning it should be closed with the proper ending tag. This has an impact on a specific feature of forms: the way you define the default value. To define the default value of an <input> element you have to use the value attribute like this:

< input type = " text " value = " by default this element is filled with this text " / >
  
< FORM >
All forms start with a < form > element. It's a container element like a < section > or < footer > element, but specifically for containing forms; it also supports some specific attributes to configure the way the form behaves
  
**addEventListener()**

Two parameters: the name of the event we want to register this handler for, and the code that comprises the handler function we want to run in response to it.
  
**EVENT**
  
Inside an event handler function, you'll see a parameter specified with a name such as event, evt, or e. This is called the event object, and it is automatically passed to event handlers to provide extra features and information.
  
## THINGS I WANT TO KNOW
-_-
GIThub doesnt like < > spaced together
  
  
