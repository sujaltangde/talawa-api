[Admin Docs](/)

***

# Variable: organizationMembershipsTableRelations

> `const` **organizationMembershipsTableRelations**: `Relations`\<`"organization_memberships"`, \{ `creator`: `One`\<`"users"`, `false`\>; `member`: `One`\<`"users"`, `true`\>; `organization`: `One`\<`"organizations"`, `true`\>; `updater`: `One`\<`"users"`, `false`\>; \}\>

Defined in: [src/drizzle/tables/organizationMemberships.ts:92](https://github.com/PalisadoesFoundation/talawa-api/blob/2cc2354b3599462f5e9976dfd00bd2cfa22095cb/src/drizzle/tables/organizationMemberships.ts#L92)
