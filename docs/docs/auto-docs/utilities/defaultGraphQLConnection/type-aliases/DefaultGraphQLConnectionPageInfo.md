[Admin Docs](/)

***

# Type Alias: DefaultGraphQLConnectionPageInfo

> **DefaultGraphQLConnectionPageInfo**: `object`

Defined in: [src/utilities/defaultGraphQLConnection.ts:134](https://github.com/PalisadoesFoundation/talawa-api/blob/be8575be3c5989d76dd2f84308de81461931796c/src/utilities/defaultGraphQLConnection.ts#L134)

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
