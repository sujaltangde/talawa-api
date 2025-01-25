[Admin Docs](/)

***

# Variable: advertisementsTableRelations

> `const` **advertisementsTableRelations**: `Relations`\<`"advertisements"`, \{ `attachmentsWhereAdvertisement`: `Many`\<`"advertisement_attachments"`\>; `creator`: `One`\<`"users"`, `false`\>; `organization`: `One`\<`"organizations"`, `true`\>; `updater`: `One`\<`"users"`, `false`\>; \}\>

Defined in: [src/drizzle/tables/advertisements.ts:111](https://github.com/PalisadoesFoundation/talawa-api/blob/c0493e690fb59bf2b3a98d1507811ac221fdc899/src/drizzle/tables/advertisements.ts#L111)
