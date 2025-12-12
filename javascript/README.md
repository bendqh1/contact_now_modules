# Base

## HTML template (starter)

```js
document.body.insertAdjacentHTML('beforeend', `
  CODE COMES HERE
`);
```

## CSS template

```css
const newStyle = document.createElement("style");
newStyle.type = "text/css";
newStyle.innerHTML +=`
  CODE COMES HERE
`;
```

## JavaScript call (ender)

```js
document.head.appendChild(newStyle);
```
