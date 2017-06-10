DESCRIPTION
-----------

A Drupal 8 Google Material Design theme
https://www.google.com/design/spec/material-design
This theme is not for front-end beginners.
Targeting extreme performance in modern browsers and new web technologies and
low-powered devices, this theme is for lightweight sites.
Use it when you are ready to move away from jQuery.
http://andreapaiola.name/2015-07-materialize-css-vs-material-design-lite/

Optional module: MDL Layout components
https://github.com/monosmou/mdl_layout


FEATURES
--------

Easy theme administration:
- You can change the MDL version, default is "1.3.0". Easy upgrade.
- You change the MDL primary color, default is "indigo".
- You change the MDL accent color, default is "pink".
- You can load the Roboto font from Google CDN. This is bad for performance, avoid if possible.
- You can load the MDL CSS/JS from Google CDN or from a local directory.
- MDL Layout Components http://www.getmdl.io/components/index.html
-- Fixed Header
-- Waterfall Header
-- Scroll Header
-- Transparent Header
-- Seamed Header
-- Fixed Drawer
-- Footer mini or mega

Web App Manifest
http://w3c.github.io/manifest/
The file manifest.json is in the theme directory, compile with your website app data

NEW FEATURES (TODOs, in development)
------------------------------------

Progressive webapp with Offline-first (e.g. IndexedDB and ServiceWorkers) and Web workers (HTTPS only)
http://addyosmani.com/blog/getting-started-with-progressive-web-apps/
https://infrequently.org/2015/06/progressive-apps-escaping-tabs-without-losing-our-soul/
http://www.pocketjavascript.com/blog/2015/11/23/introducing-pokedex-org

Performance optimization with Modern Progressive Enhancement
https://www.youtube.com/watch?v=r038QioMtxI

HTTP/2 optimizations

LAYOUT STRUCTURE: Standard Drupal 8 Regions and MDL Layout components
---------------------------------------------------------------------

https://api.drupal.org/api/drupal/core%21modules%21system%21templates%21page.html.twig/8
https://www.google.com/design/spec/layout/structure.html
http://www.getmdl.io/components/index.html#layout-section

page.header (Header)
Standard place for Site branding with logo, site name and site slogan.
In Material Design becomes the App bar / primary toolbar.

page.primary_menu (Primary menu)
Standard place for site Main navigation block, in Material Design becomes a navigation block in the header.

page.secondary_menu (Secondary menu)
Tipically the place for User account menu and users tasks, it becomes a layout block of menu type,
a hamburger menu in the header? I prefer in the drawer.
https://www.google.com/design/spec/components/menus.html
http://www.getmdl.io/components/index.html#menus-section

page.waterfall (Waterfall)
Navigation elements that disappear when scrolling down.

page.breadcrumb (Breadcrumb)
Breadcrumb navigation in content area

page.highlighted (Highlighted)
Status messages: alerts and errors messages in content area

page.help (Help)
Help messages in content area

page.content (Content)
Main page contents: contains entities fields output and main user interactions/contents

page.sidebar_first (Left sidebar) and page.sidebar_second (Right sidebar)
You can use for faceted navigations, become MDL navigation drawers.
https://www.google.com/design/spec/patterns/navigation-drawer.html
http://www.getmdl.io/components/index.html#menus-section

page.footer (Footer)
Copyright and Term of service area. Easy.


INSTALLATION
------------

Standard theme installation: copy the unzipped dir into "themes" directory.
MDL's CSS and JS are in Google CDN, but you can load from local theme subdirectory mdl/, look at the theme configuration.
Download from http://www.getmdl.io/started/index.html#download
Current MDL version: 1.3.0, but if you want you can update MDL version in theme configuration.
Default colors are indigo-pink, but MDL colors is customizable here http://www.getmdl.io/customize/index.html
and you can set in theme configuration.
