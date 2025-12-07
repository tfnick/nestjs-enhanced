# nestjs-enhanced

This repository contains several packages that enhance the functionality of NestJS:

- [@tfnick/context](./packages/context): Provides access to the current express request from anywhere.
- [@tfnick/pg-boss](./packages/pg-boss/): Decorators that provide a more 'nest' way of scheduling work with [pg-boss](https://github.com/timgit/pg-boss)
- [@tfnick/pub-sub](./packages/pub-sub/): Lightweight mechanism to send/receive messages between different nestjs services. Currently only supports postgres
- [@tfnick/sockets](./packages/sockets/): Provides easy access to active sockets from anywhere
- [@tfnick/workers](./packages/workers/): Spawn child threads/processes within nestjs
