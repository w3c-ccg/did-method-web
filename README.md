# `did:web` Decentralized Identifiers Method Spec

This repository contains the `did:web` Decentralized Identifier Method
Specification. You can access the latest version of this specification here:

https://w3c-ccg.github.io/did-method-web/

The W3C Community Group that is working on this specification can be found
here:

https://w3c-ccg.github.io/

## Editing and building the specification
The specification is built using [Bikeshed](https://tabatkins.github.io/bikeshed/).

That means: **do not edit `index.html` directly**. Only edit `index.bs`, and
generate the HTML using Bikeshed.

### Generating ReSpec HTML using `curl`

These instructions assume use of the `curl` command, but you can use any
equivalent "talk HTTP at a server" command you might have access to.

```
curl https://api.csswg.org/bikeshed/ -F file=@index.bs -F force=1 > index.html
```
