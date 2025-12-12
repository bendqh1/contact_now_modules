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

# HTML examples

## Heading

```html
<div class="sticky_global_any_contact_box">

<h2>להשאיר לי הודעה 24 שעות</h2>

<div class="always_flex">
<!-- all besides co comes here -->
</div>
    
</div>
```

## VoIP 1

```html
<div class="whatsapp_contact">
    <div class="voip_wrapper">
        <a href="https://wa.me/WHATSAPP_NUMBER_PATTERN" class="voip_link">
            <span dir="ltr" class="voip_text">WhatsApp</span>
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="voip_call_icon" class="voip_icon"></img>
        </a>
    </div>
</div>
```
