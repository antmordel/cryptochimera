# cryptochimera

An over-engineered minimal app to play with technology. This doesn't represent a guide on how you should do things. I'm just exploring all the technologies with a minimal project.

## Technology stack

- [NX Monorepo](https://nx.dev/): Manage multiple projects within a single workspace.

### Helpers

- [Toptal gitignore](https://www.toptal.com/developers/gitignore): Generate a `.gitignore` file for your project.

## Monorepo

This project uses [NX](https://nx.dev/) to manage multiple projects within a single workspace. While Nx is widely used for JavaScript/TypeScript, it can also serve as a general-purpose build orchestrator for other languages.

### Getting started with NX

```
# Install nx
npm install -g nx

# Initialize NPM in this current repo
npm init -y

# Install NX dependencies
npm install --save-dev nx @nrwl/workspace


# Create the basic NX configuration
npx nx init
```

### Misc

#### Using toptal gitignore

We can leverage their API to generate a `.gitignore` file for our project.

```bash
curl -o .gitignore https://www.toptal.com/developers/gitignore/api/node,vim
```
