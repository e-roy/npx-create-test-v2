# Just a Boilerplate Test

This npx create is just a boilerplate for testing purposes. The output files will install Next.js dependencies with a package.json and node modules. There is no app with this package, created for testing purposes

Install packages

```bash
yarn
```

To run next for development on localhost:3000

```bash
yarn dev
```

To test locally (this will install in the next-test-v2 folder)

```bash
yarn start
```

Update package

```bash
yarn update-version
```

Publish to npm

```bash
yarn publish-latest
```

For JS Next App - include files in templates/default
For TS Next App - include files in templates/typescript

# npx-test

To get started, use the following command:

```bash
npx npx-create-test-v2
```

Or, for a [TypeScript project](https://github.com/vercel/next.js/blob/canary/docs/basic-features/typescript.md):

```bash
npx npx-create-test-v2 --typescript
```

Default install is yarn, for a npm install:

```bash
npx npx-create-test-v2 --use-npm
```

To create a new app in a specific folder, you can send a name as an argument. For example, the following command will create a new Next.js app called `blog-app` in a folder with the same name:

```bash
npx npx-create-test-v2 blog-app
```
