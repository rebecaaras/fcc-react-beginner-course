1. Where does React put all of the elements I create in JSX when I 
   call `root.render()`?
    
    The elements in this case will be placed in the DOM as children of the root component.
2. What would show up in my console if I were to run this line of code:
    ```
    console.log(<h1>Hello world!</h1>)
    ```
    An object!


3. What's wrong with this code:
    ```
    root.render(
        <h1>Hi there</h1>
        <p>This is my website!</p>
    )
    ```
    The elements aren't inside a parent element.

4. What does it mean for something to be "declarative" instead of "imperative"?
    
    "Declarative" in programming means that a programmer must give detailed commands in order to perform a task, you have to tell that language exactly what to do.

    In imperative programming the level of abstraction is higher so that you can give less detailed commands to perform the same task.

5. What does it mean for something to be "composable"?

    That it can be assembled in the form of smaller components that can be reused in different tasks, like lego.