<picture>
  <source media="(prefers-color-scheme: dark)" srcset="banner-dark.svg">
  <img alt="Loomux" src="banner-light.svg" width="100%">
</picture>

Loomux is a chat interface to coding agents that run in tmux on your own
machines. You ask in a conversation; Loomux starts or picks an agent,
carries the request to it and brings its work back into the same
conversation. Because each agent lives in an ordinary tmux session, you can
SSH in and attach to it at any time, take over by hand, and hand it back.
You host all of it yourself.

| Repository | What it is |
|---|---|
| [server](https://github.com/loomux/server) | `loomuxd`: the HTTP API, the agents' tmux sessions and the routing between chat and agents |
| [web](https://github.com/loomux/web) | The web client, served by the server |
| [tui](https://github.com/loomux/tui) | `loomux`, the terminal client |

**Status: pre-alpha.** There are no releases to rely on yet, and the API
and the clients change without notice. The terminal client is at its
skeleton stage and not usable yet.

<!-- The banner files are copies of the output of docs/brand/generate.py in loomux/web. Change them there, never by hand. -->
