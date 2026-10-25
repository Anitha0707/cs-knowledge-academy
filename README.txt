CS KNOWLEDGE ACADEMY - website files
====================================
index.html   the website (open with Live Server in VS Code)
data.js      all the content (recordings, presentations, announcements, settings)
assets/      the logo and browser-tab icon (favicon)
apps/        the ready-reckoner web apps (linked from "Web Applications")
.vscode/     Live Server port setting (5501)

To publish: upload index.html, data.js and the apps folder together to your host.

Tip: to make the Subscribe pop-up open your channel directly, open Admin > Settings
and paste your YouTube channel link, then upload the new data.js.

Upcoming Sessions page now has two sections: "Tamil Sessions" and "English Sessions".
In Admin > Upcoming Sessions, choose the "Session language" for each announcement.

SEO SETUP (one-time, after you know the website address)
--------------------------------------------------------
1. Open index.html, robots.txt and sitemap.xml and replace  https://YOUR-WEBSITE-ADDRESS
   with your real address, for example  https://www.csknowledgeacademy.com
   (Use Find & Replace in VS Code: Ctrl+Shift+H, "Replace All" in the three files).
2. Upload everything (index.html, data.js, assets/, apps/, robots.txt, sitemap.xml).
3. In Google Search Console add your site, then submit  /sitemap.xml  and use "Request indexing" on the home page.
4. Add the same address to your YouTube channel "About" links and your WhatsApp business profile.
