[Admin Docs](/)

***

# Variable: eventsTableRelations

> `const` **eventsTableRelations**: `Relations`\<`"events"`, \{ `agendaFoldersWhereEvent`: `Many`\<`"agenda_folders"`\>; `attachmentsWhereEvent`: `Many`\<`"event_attachments"`\>; `creator`: `One`\<`"users"`, `false`\>; `eventAttendancesWhereEvent`: `Many`\<`"event_attendances"`\>; `organization`: `One`\<`"organizations"`, `true`\>; `updater`: `One`\<`"users"`, `false`\>; `venueBookingsWhereEvent`: `Many`\<`"venue_bookings"`\>; \}\>

Defined in: [src/drizzle/tables/events.ts:100](https://github.com/PalisadoesFoundation/talawa-api/blob/be8575be3c5989d76dd2f84308de81461931796c/src/drizzle/tables/events.ts#L100)
