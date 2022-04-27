# What is this?
This is created in order for people to learn how to scale their application to make it ready for when it grows, it covers security, common misconceptions and a generalised tutorial!

## What is this made with?
Docusaurus 2, This was an obvious choice as it's constantly updated, looks nice, is dynamic and is easy to work with! It also uses Markdown files which are common practice and are easy to learn if you don't know them.

---------

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

This builds the guide to be static files and therefore can be hosted anywhere!


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
