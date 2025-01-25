[Admin Docs](/)

***

# Function: healthcheck()

> **healthcheck**(`instance`, `opts`): `Promise`\<`void`\>

Defined in: [src/routes/healthcheck.ts:6](https://github.com/PalisadoesFoundation/talawa-api/blob/31af62eb801979353402f1e291e74768cd64d85c/src/routes/healthcheck.ts#L6)

This fastify route plugin is used to initialize a healthcheck endpoint on the fastify server for external services to check health of talawa api.

## Parameters

### instance

`FastifyInstance`\<`IncomingMessage`, `ServerResponse`\>

### opts

`Record`\<`never`, `never`\>

## Returns

`Promise`\<`void`\>
