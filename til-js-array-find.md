# JavaScript: Array find
Use `find` to get the first matching element.

```javascript
const users = [{id: 1}, {id: 2}, {id: 3}];
const user = users.find(u => u.id === 2);
console.log(user); // {id: 2}
