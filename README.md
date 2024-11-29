Append to line X in `file_b`, the content of `file_a`.

```shell
file_b='/home/hanekudai/public_html/benaharoni.com/web/core/themes/olivero/templates/layout/page.html.twig'
file_a='https://raw.githubusercontent.com/bendqh1/contact_now_modules/refs/heads/main/index.html'
sed '133 r file_b' file_a
```
