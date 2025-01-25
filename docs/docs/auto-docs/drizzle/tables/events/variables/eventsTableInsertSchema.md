[Admin Docs](/)

***

# Variable: eventsTableInsertSchema

> `const` **eventsTableInsertSchema**: `BuildSchema`\<`"insert"`, \{ `createdAt`: `PgColumn`\<\{\}, \{\}\>; `creatorId`: `PgColumn`\<\{\}, \{\}\>; `description`: `PgColumn`\<\{\}, \{\}\>; `endAt`: `PgColumn`\<\{\}, \{\}\>; `id`: `PgColumn`\<\{\}, \{\}\>; `name`: `PgColumn`\<\{\}, \{\}\>; `organizationId`: `PgColumn`\<\{\}, \{\}\>; `startAt`: `PgColumn`\<\{\}, \{\}\>; `updatedAt`: `PgColumn`\<\{\}, \{\}\>; `updaterId`: `PgColumn`\<\{\}, \{\}\>; \}, \{ `endAt`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; `name`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; `organizationId`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; `startAt`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; \}\>

Defined in: [src/drizzle/tables/events.ts:151](https://github.com/PalisadoesFoundation/talawa-api/blob/cdfbce71d27e05f54d88d4024c1f555015ff1fad/src/drizzle/tables/events.ts#L151)
