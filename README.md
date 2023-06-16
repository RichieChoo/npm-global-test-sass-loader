# npm-global-test-sass-loader
> Only has one dependencies: sass-loader

## install
```bash
npm install npm-global-test-sass-loader -g
```

## Error

If build fibers error , you will get error like:
![error](https://raw.githubusercontent.com/RichieChoo/npm-global-test-sass-loader/main/install-error.png)

## Reason
The fibers is sass-loaders optional deps， but it still is sass-loaders devDeps!! So fibers will be installed when install npm-global-test-sass-loader global.

See npm v9 doc:https://docs.npmjs.com/cli/v9/commands/npm-install?v=true

![v9](https://raw.githubusercontent.com/RichieChoo/npm-global-test-sass-loader/main/v9.png)
