Binds domain to theme and page for OctoberCMS (Mdomains v1.0.3)
===============================================================

LIVE DEMO available on http://linkonoid.com (for protecte code it`s no full version - this demo only for static pages):

Frontend domain 1: http://test1.linkonoid.com
Frontend domain 2: http://test2.linkonoid.com
Backend (admin/admin): http://linkonoid.com/backend/backend/auth/signin

Features:

- Register regular pages or static pages for domain (static pages works if Rainlab.Pages plugin install)
- Register theme for domain (does not depend on an active theme)
- Filter which domains can use backend
- It`s best way for create multiples (from 1 to out range) landings on one installations OctoberCMS

!!! WARNING !!!

For correct work, bind all domains in configurable web-server file to OctoberCMS dir (configure virtual hosts for the server Apache, Nginx or other)

Updates:

- v1.0.1 - Initialize plugin
- v1.0.2 - Adds work with Rainlab.Pages. Fixes little trubles with themes in domain settings.
- v1.0.3 - Fixes trubles with protected variables in StaticPages support. Little code refactoring.
