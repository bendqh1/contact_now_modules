```js
document.body.insertAdjacentHTML('beforeend', `
  CODE COMES HERE
`);
```

and

```css
newStyle = document.createElement("style");
newStyle.type = "text/css";
newStyle.innerHTML +=`
  CODE COMES HERE
document.head.appendChild(newStyle);
```
