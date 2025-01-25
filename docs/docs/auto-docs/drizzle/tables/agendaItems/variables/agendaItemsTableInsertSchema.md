[Admin Docs](/)

***

# Variable: agendaItemsTableInsertSchema

> `const` **agendaItemsTableInsertSchema**: `BuildSchema`\<`"insert"`, \{ `createdAt`: `PgColumn`\<\{\}, \{\}\>; `creatorId`: `PgColumn`\<\{\}, \{\}\>; `description`: `PgColumn`\<\{\}, \{\}\>; `duration`: `PgColumn`\<\{\}, \{\}\>; `folderId`: `PgColumn`\<\{\}, \{\}\>; `id`: `PgColumn`\<\{\}, \{\}\>; `key`: `PgColumn`\<\{\}, \{\}\>; `name`: `PgColumn`\<\{\}, \{\}\>; `type`: `PgColumn`\<\{\}, \{\}\>; `updatedAt`: `PgColumn`\<\{\}, \{\}\>; `updaterId`: `PgColumn`\<\{\}, \{\}\>; \}, \{ `folderId`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; `name`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; `type`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; \}\>

Defined in: [src/drizzle/tables/agendaItems.ts:124](https://github.com/PalisadoesFoundation/talawa-api/blob/be8575be3c5989d76dd2f84308de81461931796c/src/drizzle/tables/agendaItems.ts#L124)
