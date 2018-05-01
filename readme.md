### Javasrcipt has both an interpreter and compiler...
The compiler phase is the first phase and it is responsible for hoisiting as well

``````````shell
Microsoft Windows [Version 10.0.16299.371]
(c) 2017 Microsoft Corporation. All rights reserved.

D:\JavaScript\TypeScript\ts>npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (ts)
version: (1.0.0)
description:
entry point: (index.js)
test command:
git repository:
keywords:
author: Agam
license: (ISC)
About to write to D:\JavaScript\TypeScript\ts\package.json:

{
  "name": "ts",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "Agam",
  "license": "ISC"
}


Is this ok? (yes) yes

D:\JavaScript\TypeScript\ts>npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (ts) npm WARN init canceled

D:\JavaScript\TypeScript\ts>npm install
npm WARN deprecated typings@2.1.1: Typings is deprecated in favor of NPM @types -- see README for more information
npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN ts@1.0.0 No description
npm WARN ts@1.0.0 No repository field.

added 183 packages in 9.333s

D:\JavaScript\TypeScript\ts>tsc int
error TS6053: File 'int.ts' not found.

D:\JavaScript\TypeScript\ts>tsc init
error TS6053: File 'init.ts' not found.

D:\JavaScript\TypeScript\ts>tsc --init
message TS6071: Successfully created a tsconfig.json file.

D:\JavaScript\TypeScript\ts>typings

Usage: typings <command>

Commands:
    bundle, i, in, info, init, install, la, list, ll, ls, open, prune, r,
    remove, rm, search, un, uninstall, view

typings <command> -h    Get help for <command>
typings <command> -V    Enable verbose logging

typings --version       Print the CLI version
  [--loglevel] <level>  Set the log level ("debug", info", "warn", "error" or "silent")

typings@2.1.1 C:\Users\agampreetarora\AppData\Roaming\npm\node_modules\typings


D:\JavaScript\TypeScript\ts>typings install dt~core-js dt~node --global --save
core-js

node


D:\JavaScript\TypeScript\ts>npm install concurrently lite-server

> uws@9.14.0 install D:\JavaScript\TypeScript\ts\node_modules\uws
> node-gyp rebuild > build_log.txt 2>&1 || exit 0

npm WARN ts@1.0.0 No description
npm WARN ts@1.0.0 No repository field.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.3 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.3: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

+ concurrently@3.5.1
+ lite-server@2.3.0
added 223 packages and removed 182 packages in 46.295s

D:\JavaScript\TypeScript\ts>npm install concurrently lite-server
npm WARN ts@1.0.0 No description
npm WARN ts@1.0.0 No repository field.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.3 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.3: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

+ lite-server@2.3.0
+ concurrently@3.5.1
added 20 packages, removed 8 packages, updated 10 packages and moved 2 packages in 23.448s
12:13:17 - Starting compilation in watch mode...
[0]
[0]
[1] [Browsersync] Access URLs:
[1]  --------------------------------------
[1]        Local: http://localhost:3000
[1]     External: http://10.175.30.122:3000
[1]  --------------------------------------
[1]           UI: http://localhost:3001
[1]  UI External: http://10.175.30.122:3001
[0]
[0]
[0]
[1] 18.05.01 14:08:31 304 GET /index.html
[0]
[1] 18.05.01 14:14:52 304 GET /index.html
[0]
14:15:21 - File change detected. Starting incremental compilation...
[0]
[0]
[0] 14:15:21 - Compilation complete. Watching for file changes.
[0]
[0]
[1] [Browsersync] Reloading Browsers...
[1] 18.05.01 14:15:22 304 GET /index.html