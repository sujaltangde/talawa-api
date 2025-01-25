[Admin Docs](/)

***

# Function: objects()

> **objects**(`instance`, `opts`): `Promise`\<`void`\>

Defined in: [src/routes/objects.ts:9](https://github.com/PalisadoesFoundation/talawa-api/blob/c0493e690fb59bf2b3a98d1507811ac221fdc899/src/routes/objects.ts#L9)

This fastify route plugin is used to initialize a `/objects/:name` endpoint on the fastify server for clients to fetch objects from the minio server.

## Parameters

### instance

`FastifyInstance`\<`IncomingMessage`, `ServerResponse`, `TypeBoxTypeProvider`\>

### opts

`Record`\<`never`, `never`\>

## Returns

`Promise`\<`void`\>
