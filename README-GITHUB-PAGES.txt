Formulook - GitHub Pages static preview

Upload the CONTENTS of this folder to the root of the public repository.
Then enable GitHub Pages from Settings > Pages > Deploy from a branch > main > /(root).

IMPORTANT:
This is only the static frontend preview. The app's API is configured at /api/trpc.
GitHub Pages does not run Node.js or a database, so login, registration, AI tools,
admin, payments and other backend-dependent features will not work until the backend
is separately hosted and the frontend API URL is configured to point to it.
Do not upload .env files, database credentials, API keys, server.mjs or seed-owner.mjs.
