# sharp-installation-error
After running the program, due to the `require('sharp')` command, an error appears in the console:

```
Uncaught Error: 
Something went wrong installing the "sharp" module

A dynamic link library (DLL) initialization routine failed.
\\?\[path]\sharp-installation-error\src\node_modules\sharp\build\Release\sharp.node

- Remove the "node_modules/sharp" directory then run
  "npm install --ignore-scripts=false --verbose sharp" and look for errors
- Consult the installation documentation at https://sharp.pixelplumbing.com/install
- Search for this error at https://github.com/lovell/sharp/issues

    at Object.<anonymous> ([path]\sharp-installation-error\src\node_modules\sharp\lib\constructor.js:32:9)
    at Module._compile (node:internal/modules/cjs/loader:1133:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1168:10)
    at Module.load (node:internal/modules/cjs/loader:1013:32)
    at Function.Module._load (node:internal/modules/cjs/loader:853:14)
    at Module.require (node:internal/modules/cjs/loader:1037:19)
    at require (node:internal/modules/cjs/helpers:93:18)
    at Object.<anonymous> ([path]]\sharp-installation-error\src\node_modules\sharp\lib\index.js:3:15)
    at Module._compile (node:internal/modules/cjs/loader:1133:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1168:10)
```