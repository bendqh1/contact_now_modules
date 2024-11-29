Append to line X in `file_b`, the content of `file_a`.

```shell
file_to_change='/home/hanekudai/public_html/benaharoni.com/web/core/themes/olivero/templates/layout/page.html.twig'
cd www && cd benaharoni.com
wget https://raw.githubusercontent.com/bendqh1/contact_now_modules/refs/heads/main/index.html'
sed '133 r index.html' $file_to_change 
cat $file_to_chhange
rm index.html
```
