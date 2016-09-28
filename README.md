object-literal-smart-keys
=========================
TSLint rule for ordering object literal keys like in corresponding type of interface.

See [tests](https://github.com/arusakov/tslint-object-literal-smart-keys/blob/master/tests/test1.ts) for info about provided checkings. 

Install
-------
`npm i -D tslint-object-literal-smart-keys`

Example tslint.json
-------------------
```
{
    "rulesDirectory": [
        "./node_modules/tslint-object-literal-smart-keys/rules"
    ],
    "rules" {
        "object-literal-smart-keys": true
    }
}
```

Roadmap
-------
1. Tests
2. Object literal nesting
3. Complicated cases