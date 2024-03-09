---
title: Lobster LSP (Language Server Protocol)
---

Implementation
-------------------
The lobster LSP is written in typescript, and runs with NodeJs.
It calls internally the lobster compiler for the features.
> LSP simply uses [command line arguments](command_line_usage.html) from the lobster runtime.

I want to use this for X editor/IDE
--------------------------------------
Usually, you'd have to package this LSP in an addon for your preferred IDE.
See your IDE/editors documentation on how to integrate this. 
PRs are always welcome.

You compile the LSP to a final `.js` file to be executed with NodeJs by running `npm webpack` (or `npm run webpack`).

If you don't have webpack installed, you can run the following command to install webpack: `npm i webpack`.
