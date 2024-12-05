1. What is a React component?
 
 It is a function that returns jsx and can be placed anywhere at a html page, it is like a custom made html element that can also be adapted to different places.

2. What's wrong with this code?
```
function myComponent() {
    return (
        <small>I'm tiny text!</small>
    )
}
```

The function should be in pascal case: MyComponent().

3. What's wrong with this code?
```
function Header() {
    return (
        <header>
            <img src="./react-logo.png" width="40px" alt="React logo" />
        </header>
    )
}

root.render(Header())
```

It is standard to call a component like an html tag, even though the above syntax might work.
