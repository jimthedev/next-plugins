# Next.js Plugins

## Official Next.js plugins

- [@zeit/next-css](./packages/next-css)
- [@zeit/next-sass](./packages/next-sass)
- [@zeit/next-less](./packages/next-less)
- [@zeit/next-preact](./packages/next-preact)
- [@zeit/next-typescript](./packages/next-typescript)

## Community made plugins

- [next-offline](https://github.com/hanford/next-offline)

## Adding a plugin

> :warning: Before adding a plugin in this repository please create an issue to establish if it should be an official plugin or not.

1. Create a directory under the `packages` folder
2. Add `package.json` to the directory with these contents:
```
{
  "name": "@zeit/next-<NAME>",
  "version": "0.0.1",
  "main": "index.js",
  "license": "MIT",
  "repository": "zeit/next-plugins"
}
```

3. Add a `index.js` file with the plugin code
4. Add a `readme.md` explaining what the plugin does, how to install, and how to configure it
5. Submit a pull request
