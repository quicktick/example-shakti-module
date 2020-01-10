# example-shakti-module

An example [Shakti](https://shakti.com/)) module

Install [Yarn](https://yarnpkg.com/lang/en/)

```
yarn init
yarn add shakti-require
yarn add example-shakti-module
```

Then at the start of your program run:

```
\l ./node_modules/shakti-require/require.k
```

You then require other modules like this:
```
.require.require["example-shakti-module"] / loads the module from ./node_modules
.example.add[1;2]
```
