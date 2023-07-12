# @fvilers/normalize-port

An helper function to normalize a port number expressed as a string

## Installation

```
npm install @fvilers/normalize-port
```

or

```
yarn add @fvilers/normalize-port
```

# ECMAScript module

Starting with version 2.0.0, this library will be published as an ECMAScript module.

## Usage

```ts
import { normalizePort } from "@fvilers/normalize-port";

const port = normalizePort(process.env.PORT || "3000");
app.set("port", port); // `app` is an express app
```
