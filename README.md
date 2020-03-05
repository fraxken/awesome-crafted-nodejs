# awesome-crafted-nodejs
Awesome list of well crafted Node.js packages. Some others cool list that may help you:
- https://github.com/bcoe/awesome-cross-platform-nodejs
- https://github.com/lirantal/awesome-nodejs-security

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
- [terkelg](https://github.com/terkelg)

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
- [matchit](https://github.com/lukeed/matchit) - Quickly parse & match URLs
- [zup](https://github.com/mscdex/zup) - A simple, fast template engine for node.

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
- [@slimio/json-diff](https://github.com/SlimIO/json-diff) - Stdout difference from two JS Objects in the TTY
- [kleur](https://github.com/lukeed/kleur#readme) - The fastest Node.js library for formatting terminal text with ANSI colors~! (no dependencies).
- [cliui](https://github.com/yargs/cliui#readme) - easily create complex multi-column command-line-interfaces.
- [prompts](https://github.com/terkelg/prompts) - Lightweight, beautiful and user-friendly interactive prompts

### Testing & Coverage
- [tape](https://github.com/substack/tape) - tap-producing test harness for node and browsers
- [baretest](https://github.com/volument/baretest) - An extremely fast and simple JavaScript test runner.
- [c8](https://github.com/bcoe/c8#readme) - Code-coverage using Node.js' built in functionality that's compatible with Istanbul's reporters. Like nyc, c8 just magically works:

### Logging
- [pino](https://github.com/pinojs/pino) - Very low overhead Node.js logger, inspired by Bunyan.

### Tooling & dev

- [dotenv](https://github.com/motdotla/dotenv#readme) - Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env.
- [@zeit/git-hooks](https://github.com/zeit/git-hooks) - No nonsense Git hook management with 0 dep.
- [watch-my-app](https://github.com/fraxken/watchapp) - Light alternative to nodemon

### Others

- [tiny-glob](https://github.com/terkelg/tiny-glob) - Super tiny and ~350% faster alternative to node-glob
- [@lukeed/uuid](https://github.com/lukeed/uuid) - A tiny (230B), fast, and cryptographically secure UUID (v4) generator for Node and the browser
- [wrr](https://github.com/lukeed/wrr) - A tiny (148B) weighted round robin utility
- [ework](https://github.com/zakodium/ework#readme) - Execute your tasks on another thread or in parallel, with a simple to use and cross-platform (Node.js >=10 and modern browsers) API.
- [flydrive](https://github.com/Slynova-Org/flydrive) - Flexible and Fluent framework-agnostic driver based system to manage storage in Node.js
- [rfdc](https://github.com/davidmarkclements/rfdc#readme) - Really Fast Deep Clone
- 🐢 [premove](https://github.com/lukeed/premove) - A tiny (247B) utility to remove items recursively
- ⚡️ [ms](https://github.com/zeit/ms) - Use this package to easily convert various time formats to milliseconds.
- [semiver](https://github.com/lukeed/semiver) - A tiny (153B) utility to compare semver strings.
- [estree-walker](https://github.com/Rich-Harris/estree-walker) - Traverse an ESTree-compliant AST
- [sonic-boom](https://github.com/mcollina/sonic-boom) - Extremely fast utf8-only stream implementation to write to files and file descriptors.
- [@slimio/lock](https://github.com/SlimIO/Lock) - Node.js Semaphore like.
- [zen-observable](https://github.com/zenparsing/zen-observable) - An Implementation of Observables for Javascript
- [node-watch](https://github.com/yuanchuan/node-watch#readme) - A wrapper and enhancements for fs.watch.
- [bytes](https://github.com/visionmedia/bytes.js#readme) - node byte string parser
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON Schema Validator. Supports draft-04/06/07
- [isolated-vm](https://github.com/laverdet/isolated-vm) - Access to multiple isolates in nodejs
