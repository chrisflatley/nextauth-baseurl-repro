# Next Auth basePath repo

Changes made (based on next and nextauth docs, see commit for details):

- NEXTAUTH_URL is http://localhost:3000/custom-route/api/auth
- SessionProvider has basePath set
- next.config.js has basePath

Environment is already included.

```bash
npm run dev
```

Visit <http://localhost:3000/custom-route>.

Pages will render as before.

BUT... can't Sign In (will get HTTP error)

## Change to v4.18.1 to see it work:

```bash
npm i next-auth@v4.18.1
npm run dev
```
