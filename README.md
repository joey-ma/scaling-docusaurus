# scaling-docusaurus

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.
There were some changes added to a various parts of the website. See if you can catch them. Or start building your own website!

### Installation

```
npm install
```

### Local Development

```
npm start
```

or 

```
npm run start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Serve

Now that static files have been generated in "build", use the following command to test your build locally.

```
npm run serve
```

### Deployment

Using SSH:

```
USE_SSH=true npm run deploy
```

Not using SSH:

```
GIT_USER=<Your GitHub username> npm run deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
