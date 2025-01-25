[Admin Docs](/)

***

# Variable: chatsTableInsertSchema

> `const` **chatsTableInsertSchema**: `BuildSchema`\<`"insert"`, \{ `avatarMimeType`: `PgColumn`\<\{\}, \{\}\>; `avatarName`: `PgColumn`\<\{\}, \{\}\>; `createdAt`: `PgColumn`\<\{\}, \{\}\>; `creatorId`: `PgColumn`\<\{\}, \{\}\>; `description`: `PgColumn`\<\{\}, \{\}\>; `id`: `PgColumn`\<\{\}, \{\}\>; `name`: `PgColumn`\<\{\}, \{\}\>; `organizationId`: `PgColumn`\<\{\}, \{\}\>; `updatedAt`: `PgColumn`\<\{\}, \{\}\>; `updaterId`: `PgColumn`\<\{\}, \{\}\>; \}, \{ `name`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; `organizationId`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; \}\>

Defined in: [src/drizzle/tables/chats.ts:130](https://github.com/PalisadoesFoundation/talawa-api/blob/2cc2354b3599462f5e9976dfd00bd2cfa22095cb/src/drizzle/tables/chats.ts#L130)
