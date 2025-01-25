[Admin Docs](/)

***

# Function: objects()

> **objects**(`instance`, `opts`): `Promise`\<`void`\>

Defined in: [src/routes/objects.ts:9](https://github.com/PalisadoesFoundation/talawa-api/blob/31af62eb801979353402f1e291e74768cd64d85c/src/routes/objects.ts#L9)

This fastify route plugin is used to initialize a `/objects/:name` endpoint on the fastify server for clients to fetch objects from the minio server.

## Parameters

### instance

`FastifyInstance`\<`IncomingMessage`, `ServerResponse`, `TypeBoxTypeProvider`\>

### opts

`Record`\<`never`, `never`\>

## Returns

`Promise`\<`void`\>
