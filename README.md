# eslint-config-config

Generic eslint config Geta uses in their frontend projects.

## Usage

### Install

#### NPM

```cmd
npm install eslint-config-geta
```

#### Yarn

```cmd
yarn add eslint-config-geta
```

### Update your .eslintrc file

1. If you don't already have one, create a .eslintrc file.
2. Add the following to the config:
```json
{
  "extends": ["eslint-config-geta"]
}
```

or you can omit the `eslint-config` part, and extend it like this:
```json
{
  "extends": ["geta"]
}
```

Note that this config does not include parsers or non-generic things, so you might 
need to define a parser in your own config.