#Basic jQuery TodoList
------
-##Todolist with jQuery, Materlize framework, Sweet alert and font-awesome

###Learning Path
This side project is used to practice jQusery Syntax and function. So  I use jQuery to manipulate DOM.
In this todolist you can **ADD LIST**, **DELETE LIST**, **EDIT LIST**.

I use jQuery to add DOM, delete DOM and get the DOM you choose so you can edit.

1. **ADD DOM**

when you click submit button, jQuery get the text in textarea, combine with Materlize card component and add all the HTML tag to browser.

2. **DELETE DOM**

when you click delete button, jQuery just delete the DOM that you click and the child DOM inside it.

3. **EDIT DOM**

when you click edit button, Materlize popup a Modal. After you change the text jQuery just replace the text inside the DOM.

###Tricky
Why jQuery know the current list that you click?

How to let browser know that the button you click is "that button you click".

In this case, I use a counter. Whenever you submit a text, I create a unique id and bind with Card component, Modal. So you can
only use ``this`` keyword to get the button you click.

I don't know if there are better way to implement this feature.

If you have better solution, feel free to email me !
