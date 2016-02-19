# eslint-config

## Usage

```sh
$ npm i -D eslint eslint-plugin-security eslint-config-emarsys
```

Then add it to your .eslintrc

```
{
  "extends": [
    "emarsys"
  ]
}
```

## Notes

Eslint config properties like `env` or `globals` are strongly
project specific so you have to set them in your own .eslintrc file.

For instance:

```
{
  "env": {
    "browser": true
  },
  "globals": {
    "React": true
  },
  "extends": [
    "emarsys"
  ]
}
```

To get an insight how it works check the [official documentation](http://eslint.org/docs/developer-guide/shareable-configs).
