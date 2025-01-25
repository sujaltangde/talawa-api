[Admin Docs](/)

***

# Function: healthcheck()

> **healthcheck**(`instance`, `opts`): `Promise`\<`void`\>

Defined in: [src/routes/healthcheck.ts:6](https://github.com/PalisadoesFoundation/talawa-api/blob/c0493e690fb59bf2b3a98d1507811ac221fdc899/src/routes/healthcheck.ts#L6)

This fastify route plugin is used to initialize a healthcheck endpoint on the fastify server for external services to check health of talawa api.

## Parameters

### instance

`FastifyInstance`\<`IncomingMessage`, `ServerResponse`\>

### opts

`Record`\<`never`, `never`\>

## Returns

`Promise`\<`void`\>
