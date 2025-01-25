[Admin Docs](/)

***

# Variable: organizationMembershipsTableRelations

> `const` **organizationMembershipsTableRelations**: `Relations`\<`"organization_memberships"`, \{ `creator`: `One`\<`"users"`, `false`\>; `member`: `One`\<`"users"`, `true`\>; `organization`: `One`\<`"organizations"`, `true`\>; `updater`: `One`\<`"users"`, `false`\>; \}\>

Defined in: [src/drizzle/tables/organizationMemberships.ts:92](https://github.com/PalisadoesFoundation/talawa-api/blob/31af62eb801979353402f1e291e74768cd64d85c/src/drizzle/tables/organizationMemberships.ts#L92)
