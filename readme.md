
# Welcome to the Land of Misfit Renders

![fun gifs](http://storage.googleapis.com/kni.sh/trip.gif)

## Better syntax highlighting
### lowercase language identifier `javascript`
```javascript
function setUser (options) {
  const user = options.username
  return function describeUser () {
    return describe(user)
  }
}
```
### camelcase language identifier `JavaScript`
```JavaScript
function setUser (options) {
  const user = options.username
  function describeUser () {
    return describe(user)
  }
}
```

### resilient syntax highlighting, even with bugs
```jsx
import React, { Component } from "react";
import Menu, {
    Button,
    Dropdown,
    Seperator,
    DropdownItem,
} from ""maybe-a-syntax-error-here";

class Menu extends Component {
  render() {
     <Menu>
            <Button>Analysis</Button>
            <Dropdown label="options">
                <DropdownItem>option 1</DropdownItem>
                <DropdownItem>Option 2/DropdownItem>
            </Dropdown>
            <Separator />
            <Button>Help</Button>
            <Dropdown label="more options">
                <DropdownItem>option 1</DropdownItem>
                <DropdownItem>Option 2</DropdownItem>
            </Dropdown>
            <div>I'm a div</div>
        </Menu>
  }
}
```


## Bugs in HTML duplications
<h1 align="center">
  This is an H1, and it comes first
</h1>
<div align="center">
  <h2>This is an H2, and it comes second</h2>
</div>
