# awesome-crafted-nodejs
Awesome list of well crafted Node.js packages.

## Why
I created this repository to list all packages that was crafted with the goal of answering needs with less dependencies (and better performance if possible). Most of the time, it means that the package will rather meet very specific needs instead of bringing together a lot features in one package.

> ⚠️ This often results in reduced accessibility. (and sometimes harder API).

Packages that are on this list are often useful to replace popular packages (if they are matching your need for sure).

## Authors
We recommend that you follow and support these people if you are looking for similar packages.

- [lukeed](https://github.com/lukeed)
- [mscdex](https://github.com/mscdex)
- [klaussinani](https://github.com/klaussinani)
- [David Mark Clements](https://github.com/davidmarkclements)
- [Mathias Buus](https://github.com/mafintosh)
- [Rich Harris](https://github.com/Rich-Harris)
- [Matteo Collina](https://github.com/mcollina)
- [James Halliday](https://github.com/substack)
- [ljharb](https://github.com/ljharb)
- [sindresorhus](https://github.com/sindresorhus)
- [Harminder Virk](https://github.com/thetutlage)

## Legends
- 🐢 There is alternative comming on Node.js core.
- ⚡️ There is alternative comming on V8 Engine.

If there is a flag this probably mean you may consider looking for the native way of doing it (sometimes new things landed in the latest version of Node.js or V8 Engine).

## Packages

### HTTP

- [got](https://github.com/sindresorhus/got#readme) - Got is a human-friendly and powerful HTTP request library (**good replacement for request or axios**).
- [polka](https://github.com/lukeed/polka#readme) - A micro web server so fast, it'll make you dance! (good replacement for Express).
- [fastify](https://github.com/fastify/fastify) - Fast and low overhead web framework, for Node.js
- [httpie](https://github.com/lukeed/httpie#readme) - A Node.js HTTP client as easy as pie!
- [sirv](https://github.com/lukeed/sirv#readme) - An optimized middleware & CLI application for serving static files~!
- [fetch-github-repositories](https://github.com/fraxken/fetch-github-repositories) - Fetch github repositories for a given user (or organization)

You may want to take a look at these organizations, who produce quality packages and middleware for HTTP Server:
- https://github.com/hapijs
- https://github.com/fastify/fastify
- https://github.com/adonisjs

### CLI (TTY etc..)

- [qoa](https://github.com/klaussinani/qoa#readme) - Minimal interactive command-line prompts
- [sade](https://github.com/lukeed/sade) - Smooth (CLI) Operator 🎶
- [@slimio/async-cli-spinner](https://github.com/SlimIO/Async-cli-spinner) - Elegant Asynchronous Terminal (CLI) Spinner for Node.js
- [@slimio/stdin](https://github.com/SlimIO/stdin) - Node.js light, interactive and elegant input crafted for REPL experience.
- [@slimio/pretty-json](https://github.com/SlimIO/Pretty-JSON) - Stdout JSON in your terminal with colors and syntax close to yml.
- [@slimio/wcwidth](https://github.com/SlimIO/wcwidth) - Fork of wcwidth.
- [kleur](https://github.com/lukeed/kleur#readme) - The fastest Node.js library for formatting terminal text with ANSI colors~! (no dependencies).

### Testing
- [tape](https://github.com/substack/tape) - tap-producing test harness for node and browsers

### Logging
- [pino](https://github.com/pinojs/pino) - Very low overhead Node.js logger, inspired by Bunyan.

### Others

- [@zeit/git-hooks](https://github.com/zeit/git-hooks) - No nonsense Git hook management with 0 dep.
- [rfdc](https://github.com/davidmarkclements/rfdc#readme) - Really Fast Deep Clone
- 🐢 [premove](https://github.com/lukeed/premove) - A tiny (247B) utility to remove items recursively
- ⚡️ [ms](https://github.com/zeit/ms) - Use this package to easily convert various time formats to milliseconds.
- [semiver](https://github.com/lukeed/semiver) - A tiny (153B) utility to compare semver strings.
- [matchit](https://github.com/lukeed/matchit) - Quickly parse & match URLs
- [estree-walker](https://github.com/Rich-Harris/estree-walker) - Traverse an ESTree-compliant AST
- [sonic-boom](https://github.com/mcollina/sonic-boom) - Extremely fast utf8-only stream implementation to write to files and file descriptors.
- [hyperid](https://github.com/mcollina/hyperid) - Uber-fast unique id generation, for Node.js and the browser
- [@slimio/lock](https://github.com/SlimIO/Lock) - Node.js Semaphore like.
- [zen-observable](https://github.com/zenparsing/zen-observable) - An Implementation of Observables for Javascript
- [node-watch](https://github.com/yuanchuan/node-watch#readme) - A wrapper and enhancements for fs.watch.
- [bytes](https://github.com/visionmedia/bytes.js#readme) - node byte string parser
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON Schema Validator. Supports draft-04/06/07 
- [zup](https://github.com/mscdex/zup) - A simple, fast template engine for node.
