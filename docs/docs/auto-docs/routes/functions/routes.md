[Admin Docs](/)

***

# Function: routes()

> **routes**(`fastify`): `Promise`\<`void`\>

Defined in: [src/routes/index.ts:13](https://github.com/PalisadoesFoundation/talawa-api/blob/be8575be3c5989d76dd2f84308de81461931796c/src/routes/index.ts#L13)

This fastify plugin function contains all talawa api routes within it.

## Parameters

### fastify

`FastifyInstance`\<`IncomingMessage`, `ServerResponse`\>

## Returns

`Promise`\<`void`\>

## Example

```ts
import routes from "./routes/index";
fastify.register(routes, {});
```
