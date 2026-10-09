USA TRUCKING LLC — HOSTINGER NODE.JS DEPLOYMENT

WHAT IS INCLUDED
- server.js: Node.js web server; serves the prebuilt website and uses Hostinger's PORT variable.
- package.json: Hostinger-recognized app metadata and the "npm start" command.
- public/: production website files, images, favicon, and robots.txt.

DEPLOY WITH HOSTINGER WEB APPS
1. In hPanel, open Websites > Add Website > Node.js web app.
2. Choose Upload your files and upload this ZIP archive.
3. Use Node.js 22 (or another supported version, 18 or newer).
4. If Hostinger asks for a framework preset, select Other.
5. Set the entry file to server.js. Use npm start as the start command.
6. No build command is needed: the production website is already included in public/.
7. Deploy and open the assigned domain to verify the site.

The archive has package.json and server.js at its root, not inside an extra
containing folder. It has no runtime npm dependencies and needs no .env file.

IMPORTANT
The contact form is a front-end demonstration only. It does not send or save
inquiries. Until a form delivery method is connected, visitors should call
+1 307-266-3094.

Hostinger's managed Node.js Web App flow requires a plan that supports Node.js
Web Apps. On a VPS, upload/extract the same archive, run "npm start" with
PORT set by your process manager or reverse proxy, and configure the domain
proxy separately.
