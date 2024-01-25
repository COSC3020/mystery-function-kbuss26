[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/GDPVb20V)
# Mystery Function

What does the `mystery()` function in the following piece of code do? Add your
answer to this markdown file.

```javascript
function mystery(a) {
    if(a.length == 1) return a[0];
    var foo = mystery(a.slice(1, a.length))
    if(foo > a[0]) return foo;
    else return a[0];
}
```
## My Answer

<p>This mystery function recursively finds the greatest element in a list, where the base case of one element returns said element. The recursive part of the function comes from the declaration of "foo", where the function executes its code with the list abridged by one. The return value of "foo" is then check if it is greater than the first list element, and returns the function return value if true and the first list element if false.<br>

Sources:<br>

https://www.markdownguide.org/basic-syntax/
