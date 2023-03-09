<div align="center">
  <br />

![GraphQLOverWebSocket](https://user-images.githubusercontent.com/25294569/94527042-172dba00-023f-11eb-944b-88c0bd58a8d2.gif)

  <h6>Coherent, zero-dependency, lazy, simple, <a href="PROTOCOL.md">GraphQL over WebSocket Protocol</a> compliant server and client.</h6>

[![Continuous integration](https://github.com/enisdenjo/graphql-ws/workflows/Continuous%20integration/badge.svg)](https://github.com/enisdenjo/graphql-ws/actions?query=workflow%3A%22Continuous+integration%22) [![graphql-ws](https://img.shields.io/npm/v/graphql-ws.svg?label=graphql-ws&logo=npm)](https://www.npmjs.com/package/graphql-ws)

<i>Use [Server-Sent Events (SSE)](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events) instead? Check out <b>[graphql-sse](https://github.com/enisdenjo/graphql-sse)</b>!</i>

  <br />
</div>

## [Get started](https://the-guild.dev/graphql/ws/get-started)

Swiftly start with the [get started guide on the website](https://the-guild.dev/graphql/ws/get-started).

## [Recipes](https://the-guild.dev/graphql/ws/recipes)

Short and concise code snippets for starting with common use-cases. [Available on the website.](https://the-guild.dev/graphql/ws/recipes)

## [Documentation](https://the-guild.dev/graphql/ws/docs)

Check the [website docs folder](website/src/pages/docs) out for [TypeDoc](https://typedoc.org) generated documentation and the [website for the render](https://the-guild.dev/graphql/ws/docs).

## [How does it work?](PROTOCOL.md)

Read about the exact transport intricacies used by the library in the [GraphQL over WebSocket Protocol document](PROTOCOL.md).

## [Want to help?](CONTRIBUTING.md)

File a bug, contribute with code, or improve documentation? Read up on our guidelines for [contributing](CONTRIBUTING.md) and drive development with `yarn test --watch` away!

## Disclaimer

This library and the [GraphQL over WebSocket Protocol](https://github.com/enisdenjo/graphql-ws/blob/master/PROTOCOL.md) are **not** cross-compatible with the [deprecated `subscriptions-transport-ws`](https://github.com/apollographql/subscriptions-transport-ws) and its [accompanying Protocol](https://github.com/apollographql/subscriptions-transport-ws/blob/master/PROTOCOL.md).

You must use `graphql-ws` coherently and implement the [GraphQL over WebSocket Protocol](https://github.com/enisdenjo/graphql-ws/blob/master/PROTOCOL.md) on both sides, server and the client.
