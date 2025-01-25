[Admin Docs](/)

***

# Function: graphql()

> **graphql**(`fastify`): `Promise`\<`void`\>

Defined in: [src/routes/graphql.ts:83](https://github.com/PalisadoesFoundation/talawa-api/blob/be8575be3c5989d76dd2f84308de81461931796c/src/routes/graphql.ts#L83)

This fastify route plugin function is initializes mercurius on the fastify instance and directs incoming requests on the `/graphql` route to it.

## Parameters

### fastify

`FastifyInstance`\<`IncomingMessage`, `ServerResponse`\>

## Returns

`Promise`\<`void`\>
