# Cloud Foundry Lerna Demo



## Steps
```bash
    cd packages/my-lib
    npm install
    cd ../packages/my-app
    npm install
    npm ls
```


## Result

```
@my/app@1.0.0 /home/mchelen/tmp/cf-lerna-demo/packages/my-app
├─┬ @my/lib@1.0.0 -> /home/mchelen/tmp/cf-lerna-demo/packages/my-lib
│ └── UNMET DEPENDENCY lodash@^4.17.15
└─┬ bunyan@1.8.12
  ├─┬ dtrace-provider@0.8.7
  │ └── nan@2.14.0
  ├── moment@2.24.0
  ├─┬ mv@2.1.1
  │ ├─┬ mkdirp@0.5.1
  │ │ └── minimist@0.0.8
  │ ├── ncp@2.0.0
  │ └─┬ rimraf@2.4.5
  │   └─┬ glob@6.0.4
  │     ├─┬ inflight@1.0.6
  │     │ ├── once@1.4.0 deduped
  │     │ └── wrappy@1.0.2
  │     ├── inherits@2.0.4
  │     ├─┬ minimatch@3.0.4
  │     │ └─┬ brace-expansion@1.1.11
  │     │   ├── balanced-match@1.0.0
  │     │   └── concat-map@0.0.1
  │     ├─┬ once@1.4.0
  │     │ └── wrappy@1.0.2 deduped
  │     └── path-is-absolute@1.0.1
  └── safe-json-stringify@1.2.0

npm ERR! missing: lodash@^4.17.15, required by @my/lib@1.0.0

```
