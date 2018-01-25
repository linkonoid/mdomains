Binds domain to theme and page for OctoberCMS (Mdomains v1.0.3)
===============================================================

LIVE DEMO for 3 different installed themes available on http://linkonoid.com (it` full current version 1.0.3 - works on Linux Caddy-server in production mode and use SQLite-storage):

- Front-end base OctoberCms domain on current active theme: http://linkonoid.com
- Front-end domain 1: http://test1.linkonoid.com
- Front-end domain 1 (Ajax page Demo theme): http://test1.linkonoid.com/ajax
- Front-end domain 2: http://test2.linkonoid.com
- Front-end domain 3: http://test3.linkonoid.com
- Front-end domain 3 (404 page Clean theme): http://test3.linkonoid.com/404
- Back-end (admin/admin): http://linkonoid.com/backend/backend/auth/signin

Attention!!! You need to understand that in order to use this plug-in, you must first register DNS-records A or CNAME and writes virtual hosts on the server (all domains must be registered in the server configuration as virtual hosts with the same parameters as the primary domain). Currently, work is underway to create a server where plugin will automatically write DNS-records on DNS-provider (in current works prototype - Cloudflare) and be registered in the server configuration file when changes are made to the plug-in's settings. This functionality will be in the new plugin, which includes all the capabilities of the current (working title - LandingCreator) and will include more other functions.

Features:

- Register regular pages or static pages for domain or url (static pages works if Rainlab.Pages plugin install)
- Register theme for domain or url (does not depend on an active theme)
- Filter which domains can use backend
- It`s best way for create multiples (from 1 to out range) landings on one installations OctoberCMS

Updates:

- v1.0.1 - Initialize plugin
- v1.0.2 - Adds work with Rainlab.Pages. Fixes little trubles with themes in domain settings.
- v1.0.3 - Fixes trubles with protected variables in StaticPages support. Little code refactoring.

