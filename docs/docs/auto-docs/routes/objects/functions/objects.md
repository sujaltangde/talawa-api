[Admin Docs](/)

***

# Function: objects()

> **objects**(`instance`, `opts`): `Promise`\<`void`\>

Defined in: [src/routes/objects.ts:9](https://github.com/PalisadoesFoundation/talawa-api/blob/a88e9b37389a25702f1dcb39c566193904da08be/src/routes/objects.ts#L9)

This fastify route plugin is used to initialize a `/objects/:name` endpoint on the fastify server for clients to fetch objects from the minio server.

## Parameters

### instance

`FastifyInstance`\<`IncomingMessage`, `ServerResponse`, `TypeBoxTypeProvider`\>

### opts

`Record`\<`never`, `never`\>

## Returns

`Promise`\<`void`\>
