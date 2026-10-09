MyUTME redesigned website — full package

This ZIP includes both the redesigned study experience and the complete original MyUTME app.

- Open index.html for the redesigned experience.
- Choose “Full original app” in the redesigned app’s sidebar to open the original feature suite at original-app/index.html.
- The original app, its data files, offline database, service worker, legal pages, and assets are retained under original-app/.
- The redesigned app, its data, install manifest, icons, and offline worker are at the ZIP root.

To publish it:
1. Extract the ZIP.
2. Upload the contents of this folder (not an extra enclosing folder) to the root of your static website host.
3. Keep all folders and files together.
4. Configure your host to serve index.html for app routes such as /practice and /resources. The included 404.html provides a fallback on hosts that use the standard 404 page for client-side routes.

The original app keeps its existing remote-service configuration. Features that depend on that service require it to remain active and correctly permissioned. Progress in the redesigned app is stored in the current browser.
