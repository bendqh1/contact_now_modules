## HTML in JavaScript

```js
document.body.insertAdjacentHTML('beforeend', `
  CODE COMES HERE
`);
```

## CSS in JavaScript

```css
const newStyle = document.createElement("style");
newStyle.type = "text/css";
newStyle.innerHTML +=`
  CODE COMES HERE
`;
```

## JavaScript appending

```js
document.head.appendChild(newStyle);
```
