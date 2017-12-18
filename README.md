Binds domain to theme and page for OctoberCMS (Mdomains v1.0.1)
===============================================================

Features:
- Register cms-pages for domain
- Register default theme for domain
- Filter which domains can use backend
- Best way for create multiples landings on one installations OctoberCMS

Announcement Mdomains v1.0.2:
- In version 1.0.2 added works with static-pages Rainlab.Pages

Greetings to all PHP OctoberCMS developers!
Announcement FREE CaddyWinPHPServer (Caddy server + PHP7 in FastCGI mode + OctoberCMS & Sqlite for storage this CMS)

Today in an hour sketched a prototype of a Windows server based on the Caddy server for PHP-developers on OctoberCMS (Caddy server + PHP7 in FastCGI mode + OctoberCMS & Sqlite for storage this CMS). Assembly can also be used in production, works stably (this is Caddy && Golang!). Its free for all on Github: https://github.com/linkonoid/caddywinphpserver

Installation - not required: extract archive (caddywinphpserver.zip + download parts caddywinphpserver.z01 caddywinphpserver.z02) and just run caddywinphpserver.exe!!! To go to the OctoberCMS Admin Panel select the top item of the program menu from the tray (admin/admin). It's new installation. In some cases (if not), use the hostseditor.exe utility (also launched from the tray menu) to register localhost (127.0.0.1) in the hosts file. Successful work!

The project includes 2 utilities from the winginx project (hostseditor.exe and php-config.exe).

P.S. This is an assembly for Win64. It is also possible to add support for Win32, MySQL, Redis, Node etc. (15 minutes of work).
