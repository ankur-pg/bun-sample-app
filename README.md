# bun-sample-app

### https://github.com/ankur-pg/bun-sample-app

### About Bun

Two weeks ago, Bun was released and took the Node.js world by storm. It's a JavaScript runtime and toolkit, like Node.js

It's a drop in replacement for Node. When you replace Node with Bun your application will continue to work fine. It's backward compatible.

Bun 1.0 is a toolkit to build and run JavaScript and TypeScript apps.

It aims to simplify and eliminate unnecessary complexity while retaining the best parts of the Javascript ecosystem.

### Why Bun ?

1. The primary driving force to create Bun was performance imporvement over Node. Example - a simple console.log runs 4 times faster in Bun.
2. It boasts faster package installation and file operations compared to Node.
3. It comes with a set of optimised APIs to help with tasks like server start or working with files.
4. It supports Typescript and other modules out of box. No dependencies needed.

### How come it's so Fast ?

1. Bun uses a more performant JS engine. Bun uses Apple’s JavaScriptCore which was built for Safari. While Node uses Google’s V8.
2. Other smart choices include - after each task is completed in Bun's event loop, it checks if the memory usage went up and schedules the Garbage Collection (in addition to the automatic one)

### Ready for DEMO ? Let's build a simple App

### Install

curl -fsSL https://bun.sh/install | bash -s "bun-v1.0.2"
