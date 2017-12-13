Binds domain to theme and page for OctoberCMS (Mdomains v1.0.1)
===============================================================

Features:
- Register cms-pages for domain 
- Register default theme for domain
- Filter which domains can use backend
- Best way for create multiples landings on one installations OctoberCMS

Announcement Mdomains v1.0.2:
- In version 1.0.2 added works with static-pages Rainlab.Pages
- Test in production 

For correct work, make all virtual hosts on your server (if test domains on local PC - write in юhosts this domains).
This correct Config file for my test Caddy server:

http://test.ru, http://test1.ru, http://test2.ru, http://test3.ru {
tls admin@test.ru
root ./caddy/cms
gzip
log ./logs/test.ru_log
errors ./logs/test.ru_err_log
fastcgi / 127.0.0.1:9000 php {
index index.php
}
rewrite {
to {path} {path}/ /index.php?{query}
}
}

OctoberCMS root: './caddy/cms', all works OK on my Windows PC and OctoberCMS with embedded sqlite storage (Apache, Nginx - evil...it is very hard to tune for non admin users:)

Best regards, your Max Barulin, aka Linkonoid (https://github.com/linkonoid)

P.S. I write applications in the languages of Golang, Freepascal/Lazarus, Dart (flutter), and PHP.
If you need to write a plugin for the caddy server, OctoberCMS, a visual app on Golang or Lazarus - write to me on mail: max@linkonoid.com
