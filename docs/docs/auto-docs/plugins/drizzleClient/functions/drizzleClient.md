[Admin Docs](/)

***

# Function: drizzleClient()

> **drizzleClient**(`fastify`): `Promise`\<`void`\>

Defined in: [src/plugins/drizzleClient.ts:22](https://github.com/PalisadoesFoundation/talawa-api/blob/be8575be3c5989d76dd2f84308de81461931796c/src/plugins/drizzleClient.ts#L22)

Integrates a drizzle client instance on a namespace `drizzleClient` on the global fastify instance.

## Parameters

### fastify

`FastifyInstance`\<`IncomingMessage`, `ServerResponse`\>

## Returns

`Promise`\<`void`\>

## Example

```ts
import drizzleClientPlugin from "~/src/plugins/drizzleClient";

fastify.register(drizzleClientPlugin, {});
const user = await fastify.drizzleClient.query.usersTable.findFirst();
```
