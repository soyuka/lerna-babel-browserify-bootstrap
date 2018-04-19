Relative imports aliases:

https://github.com/tleunen/babel-plugin-module-resolver

`.babelrc` example:

```
{
    "presets": ["env"],
    "plugins": [
        ["module-resolver", {
            "root": ["./src"],
            "alias": {
                "@core": "./src/core",
                "@components": "./src/components",
                "@auth": "./src/components/auth",
                "@utils": "./src/components/utils"
            }
        }]
    ]
}
```
