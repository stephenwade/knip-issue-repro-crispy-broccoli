# knip-issue-repro-crispy-broccoli

```console
$ npm ci
...
$ npm run knip

> knip
> knip

✂️  Excellent, Knip found no issues.
$ npx -y npm-check-updates knip -u
...
 knip  5.27.3  →  5.29.2

Run npm install to install new versions.
$ npm install
...
$ npm run knip

> knip
> knip

Unlisted dependencies (1)
node_modules/react-toastify/dist/components  app/ToastContainer.tsx
Configuration issues (1)
Unused item in ignoreDependencies: node_modules/react-toastify/dist/components
```
