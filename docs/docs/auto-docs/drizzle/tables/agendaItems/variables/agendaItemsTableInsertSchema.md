[Admin Docs](/)

***

# Variable: agendaItemsTableInsertSchema

> `const` **agendaItemsTableInsertSchema**: `BuildSchema`\<`"insert"`, \{ `createdAt`: `PgColumn`\<\{\}, \{\}\>; `creatorId`: `PgColumn`\<\{\}, \{\}\>; `description`: `PgColumn`\<\{\}, \{\}\>; `duration`: `PgColumn`\<\{\}, \{\}\>; `folderId`: `PgColumn`\<\{\}, \{\}\>; `id`: `PgColumn`\<\{\}, \{\}\>; `key`: `PgColumn`\<\{\}, \{\}\>; `name`: `PgColumn`\<\{\}, \{\}\>; `type`: `PgColumn`\<\{\}, \{\}\>; `updatedAt`: `PgColumn`\<\{\}, \{\}\>; `updaterId`: `PgColumn`\<\{\}, \{\}\>; \}, \{ `folderId`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; `name`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; `type`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; \}\>

Defined in: [src/drizzle/tables/agendaItems.ts:124](https://github.com/PalisadoesFoundation/talawa-api/blob/c0493e690fb59bf2b3a98d1507811ac221fdc899/src/drizzle/tables/agendaItems.ts#L124)
