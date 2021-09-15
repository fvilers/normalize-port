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

## Usage

```ts
import normalizePort from "@fvilers/normalize-port";

const port = normalizePort(process.env.PORT || "3000");
app.set("port", port); // `app` is an express app
```
