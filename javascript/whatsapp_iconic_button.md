
```
document.body.insertAdjacentHTML('beforeend', `
	<aside class="jcb_button">
		<a class="jcb_phone_link" href="https://wa.me/NUMBER">
			<img class="jcb_phone_icon" src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg"></img>
		</a>
	</aside>
`);

newStyle = document.createElement("style");
newStyle.type = "text/css";
newStyle.innerHTML +=`
    .jcb_button {
        display: block;
        position: fixed;
        bottom: 22.5px;
        left: -22.5px; // Note the minus.
        z-index: 2147483647;
        width: 10%;
        height: 60px;
        text-align: center;
        text-decoration: none;
        font-size: 120%;
        font-weight: bold;
        color: #fff;
        text-shadow: 0 1px 0px rgb(0 0 0 / 18%);
    }
    .jcb_phone_link {
        color: white !important;
        text-decoration: none !important;
    }
    .jcb_phone_icon {
        width: 60px;
        height: 60px;
	max-width: unset;
    }

    @media screen and (max-width: 999px) {
        .jcb_button {
            left: 50px;
        }
    }
`;

document.head.appendChild(newStyle);
```
