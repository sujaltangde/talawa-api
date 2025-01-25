[Admin Docs](/)

***

# Variable: eventsTableRelations

> `const` **eventsTableRelations**: `Relations`\<`"events"`, \{ `agendaFoldersWhereEvent`: `Many`\<`"agenda_folders"`\>; `attachmentsWhereEvent`: `Many`\<`"event_attachments"`\>; `creator`: `One`\<`"users"`, `false`\>; `eventAttendancesWhereEvent`: `Many`\<`"event_attendances"`\>; `organization`: `One`\<`"organizations"`, `true`\>; `updater`: `One`\<`"users"`, `false`\>; `venueBookingsWhereEvent`: `Many`\<`"venue_bookings"`\>; \}\>

Defined in: [src/drizzle/tables/events.ts:100](https://github.com/PalisadoesFoundation/talawa-api/blob/cdfbce71d27e05f54d88d4024c1f555015ff1fad/src/drizzle/tables/events.ts#L100)
