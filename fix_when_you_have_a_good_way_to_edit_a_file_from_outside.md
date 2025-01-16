Append to line X in `file_b`, the content of `file_a`.

```shell
file_to_change='/home/hanekudai/public_html/benaharoni.com/web/core/themes/olivero/templates/layout/page.html.twig'
cd www && cd benaharoni.com
wget https://raw.githubusercontent.com/bendqh1/contact_now_modules/refs/heads/main/index.html'
sed "133r $file_to_change" index.html 
cat --number $file_to_change
rm index.html
```
