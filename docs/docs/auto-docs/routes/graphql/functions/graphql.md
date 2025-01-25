[Admin Docs](/)

***

# Function: graphql()

> **graphql**(`fastify`): `Promise`\<`void`\>

Defined in: [src/routes/graphql.ts:83](https://github.com/PalisadoesFoundation/talawa-api/blob/5c2e90552414053c7e52a1a2621c3724f43bf6ad/src/routes/graphql.ts#L83)

This fastify route plugin function is initializes mercurius on the fastify instance and directs incoming requests on the `/graphql` route to it.

## Parameters

### fastify

`FastifyInstance`\<`IncomingMessage`, `ServerResponse`\>

## Returns

`Promise`\<`void`\>
