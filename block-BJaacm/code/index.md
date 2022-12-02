```js
let user = {
  name: 'Arya',
  sibling: ['Robb', 'Ryan', 'John'],
};
let allBrothers = ['Robb', 'Ryan', 'John'];
let brothersCopy = user.sibling;
let usename = user.name;
let newUser = user;
```

1. Memory representation

- Create the memory representation of the above snippet on notebook.
- Take a photo/screenshot and add it to the folder `code`

<!-- To add this image here use ![name](./hello.jpg) -->

2. Answer the following with reason:

- `user == newUser;` //   true because newUser has a value of user 
- `user === newUser;`// true because newUser has a value of user 
- `user.name === newUser.name;`  // true because newUser has a value of user 
- `user.name == newUser.name;`  // true because newUser has a value of user 
- `user.sibling == newUser.sibling;`  // true because newUser has a value of user 
- `user.sibling === newUser.sibling;`  // true because newUser has a value of user 
- `user.sibling == allBrothers;` // false because user has a different address and allBrothers has a differrent address .
- `user.sibling === allBrothers;` // false because user has a different address and allBrothers has a differrent address .
- `brothersCopy === allBrothers;` // false because brothersCopy has the value of user.sibling andu user object points to a different address .
- `brothersCopy == allBrothers;` // false because brothersCopy has the value of user.sibling andu user object points to a different address .
- `brothersCopy == user.sibling;` // true because brothersCopy has the valuse of user.sibling 
- `brothersCopy === user.sibling;` // true because brothersCopy has the valuse of user.sibling 
- `brothersCopy[0] === user.sibling[0];`// true because brothersCopy has the valuse of user.sibling 
- `brothersCopy[1] === user.sibling[1];`// true because brothersCopy has the valuse of user.sibling 
- `user.sibling[1] === newUser.sibling[1];` //   true because newUser has a value of user 
