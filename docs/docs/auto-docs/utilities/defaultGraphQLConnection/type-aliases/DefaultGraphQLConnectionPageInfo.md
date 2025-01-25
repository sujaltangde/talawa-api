[Admin Docs](/)

***

# Type Alias: DefaultGraphQLConnectionPageInfo

> **DefaultGraphQLConnectionPageInfo**: `object`

Defined in: [src/utilities/defaultGraphQLConnection.ts:134](https://github.com/PalisadoesFoundation/talawa-api/blob/5c2e90552414053c7e52a1a2621c3724f43bf6ad/src/utilities/defaultGraphQLConnection.ts#L134)

This is typescript type of a base graphql connection page info object. This connection page info object can be extended to create a custom connnection page info object as long as the new connection object adheres to the default type of this base connection object.

## Type declaration

### endCursor

> **endCursor**: `string` \| `null`

### hasNextPage

> **hasNextPage**: `boolean`

### hasPreviousPage

> **hasPreviousPage**: `boolean`

### startCursor

> **startCursor**: `string` \| `null`
