# say-hello

## To test

```bash
cd path/to/say-hello
npm link
```

then

```bash
cd path/to/test-say-hello
npm init -y
npm link say-hello
```

## To publish

```
npm login
npm publish --access public
```
