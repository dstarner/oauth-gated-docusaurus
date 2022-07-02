# OAuth-Gated Docusaurus Documentation Site

This project hosts a Docusaurus documentation-only static-site on Heroku and forces an
authenticated session against an OAuth provider.

View [the associated blog post for this repository on Dev.to](https://dev.to/dan_starner/easily-serve-internal-documentation-behind-oauth-authentication-322k).

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
