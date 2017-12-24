# @neo-one/csharp

> Binary wrapper for [neon](https://github.com/neo-one-suite/neo-compiler/tree/master/neon) - C# compiler for the NEO Virtual Machine

OS X, Linux and Windows binaries are currently provided.


## CLI

```
$ npm install --global @neo-one/csharp
```

```
$ neo-one-csharp sc.dll
```


## API

```
$ npm install --save @neo-one/csharp
```

```js
const execFile = require('child_process').execFile;
const csharp = require('@neo-one/csharp');

execFile(csharp, ['sc.dll'], (err, stdout) => {
  console.log(stdout);
});
```


## License

@neo-one/csharp is MIT-licensed.
