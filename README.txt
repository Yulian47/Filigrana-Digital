FILIGRANA DIGITAL — статичний двомовний сайт (NO / EN)

1) Замініть домен-заглушку https://www.example.com на ваш справжній у всіх файлах
   (canonical, hreflang, sitemap.xml, robots.txt, JSON-LD). Або скажіть домен — я перезберу.
2) Замініть hello@example.com, +47 000 00 000, орг. номер та адресу.
3) Завантажте вміст папки на статичний хостинг (Cloudflare Pages / Netlify / будь-який).
   _headers: кеш активів на 1 рік, безпекові заголовки. _redirects: / -> /no/ або /en/ за мовою браузера (Netlify).
4) Додайте сайт у Google Search Console і надішліть sitemap.xml.
Структура: /no/ (норвезька), /en/ (англійська), /assets/ (CSS, JS, зображення з хешем у назві).
