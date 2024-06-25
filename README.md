Embedded loader for sqlite3:
Yes, you can bundle an entire Express/Fastify or NestJS or other powered server into a single js executable, without need in node_modules folder.
This loader allows you to bundle sqlite3 into an additional .node file in your dist folder. For example:

Use node-loader to load sqlite3.node file.

Supported versions: sqlite3 5.1.7 => sqlite3-embedded-loader 1.0.0

This is an alternative to the sqlite3-loader package, which allowed bundling sqlite3 with webpack on sqlite3 versions <= 5.1.6.
Unfortunately, cross-compilation is not supported.