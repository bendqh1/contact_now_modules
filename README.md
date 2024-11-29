Append to line X in `file_b`, the content of `file_a`.

```shell
cd SOMEWHERE
file_a='/home/hanekudai/public_html/benaharoni.com/web/core/themes/olivero/templates/layout/page.html.twig'
file_b='https://raw.githubusercontent.com/bendqh1/contact_now_modules/refs/heads/main/index.html'
wget $file_b
sed '133 r $file_b' $file_a
```
