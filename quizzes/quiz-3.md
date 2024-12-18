# Reusable Components - Props

1. What do props help us accomplish?

    To include unique properties to a component while maintaining the same appearance. Long story short: making it reusable.

2. How do you pass a prop into a component?
    
    As an html element property:
    `<MyComponent prop1="prop 1 here" prop2="prop 2 here" prop3="prop 3 here"/>`
    and so on...


3. Can I pass a custom prop (e.g. `blahblahblah={true}`) to a native DOM element? Why or why not?
   
    No, you can't. It will be ignored by the interpreter because it isn't a predefined property.   

4. How do I receive props in a component?

    ```
    function Navbar(props) {
        return (
            <header>
                {props.item1}
            </header>
        )
    }
    ```

    As a regular json object.

5. What data type is `props` when the component receives it?
    
    A regular json object.