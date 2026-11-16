# popopxmq-js

🚧 JavaScript SMP protocol client and agent 🏗

[![build](https://github.com/popopx-chat/popopxmq-js/workflows/build/badge.svg)](https://github.com/popopx-chat/popopxmq-js/actions?query=workflow%3Abuild)

This repository is a fork of SimpleXMQ, SimpleX Chat's JavaScript SMP client
(<https://github.com/simplex-chat/simplexmq-js>), kept under the POPOPX project name. The protocol, the
implementation and the AGPL-3.0-only licence are upstream's; see `LICENSE`.

The package is not published yet: `npm install popopxmq` will not resolve until this fork publishes it, and no
part of POPOPX Chat depends on it - the apps and SDKs use the Haskell core through
`packages/popopx-chat-nodejs` and `packages/popopx-chat-python`.

Specification: the transport handshake implemented in `src/transport.ts` is described in
<https://github.com/popopx-chat/popopxmq/blob/master/protocol/popopx-messaging.md#transport-handshake>.
