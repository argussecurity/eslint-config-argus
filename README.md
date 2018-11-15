# eslint configs

Configs based on [eslint-config-airbnb](https://www.npmjs.com/package/eslint-config-airbnb)

## Usage

Install package in your project:

```
yarn add -D git+https://argussecurity@bitbucket.org/argussecurity/eslint-config-argus.git#X.X.X
```

(where `X.X.X` is desired version)

Create `.eslintrc`:

```
{
    "extends": "argus"
}
```


## Releasing new version

Notice, that projects depends on specific version of this config.
Therefore you should always update `vesrion` in `package.json`
and then update version in relevant projects.

## How correctly upgrade those configs

*Notice*, this project does not uses `yarn.lock` since in order to correctly update it we need to run specific command,
that will rely on `npm-lock`.

In order to upgrade them you will need to use specific versions of each dependency.
See [airbnb package page](https://www.npmjs.com/package/eslint-config-airbnb) for more information.
