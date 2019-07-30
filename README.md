# Cloud Foundry Lerna Demo



## Steps
```bash
    npm install
    npm run bootstrap
    npm cf:login
    cf push
```


## Result

```
   npm ERR! code E404
   npm ERR! 404 Not Found - GET https://registry.npmjs.org/@my%2flib - Not found
   npm ERR! 404 
   npm ERR! 404  '@my/lib@^1.0.0' is not in the npm registry.
   npm ERR! 404 You should bug the author to publish it (or use the name yourself!)
   npm ERR! 404 It was specified as a dependency of 'app'
   npm ERR! 404 
   npm ERR! 404 Note that you can also install from a
   npm ERR! 404 tarball, folder, http url, or git url.
   npm ERR! A complete log of this run can be found in:
   npm ERR!     /home/vcap/.npm/_logs/2019-07-30T21_17_11_054Z-debug.log
          **ERROR** Unable to build dependencies: exit status 1
   Failed to compile droplet: Failed to run all supply scripts: exit status 14
```