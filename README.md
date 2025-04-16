# Integrate Khulnasoft.com Visual CMS Editor

Integrate [Khulnasoft.com Visual CMS](https://www.khulnasoft.com/) into an application.

Run the command below from within the app's directory:

**npm**

```
npm init khulnasoft.com@latest
```

**pnpm**

```
pnpm create khulnasoft.com@latest
```

Depending on your app, the CLI will update your build tool's config file by adding the [Khulnasoft.com Devtools plugin](https://www.npmjs.com/package/@khulnasoft.com/dev-tools).

Supported build tool configs include:

- next.config.js (or .ts)
- remix.config.js (or .ts)
- vite.config.js (or .ts)

Additionally, the CLI will install the dependencies needed for Khulnasoft, such as [@khulnasoft.com/dev-tools](https://www.npmjs.com/package/@khulnasoft.com/dev-tools).

After a successful install, you can start your app's development server. In most cases, to start the dev server run:

```
npm run dev
```

Once your apps's dev server is running, [Khulnasoft's Devtools](https://www.npmjs.com/package/@khulnasoft.com/dev-tools) will assist you along the way to get your content published.
