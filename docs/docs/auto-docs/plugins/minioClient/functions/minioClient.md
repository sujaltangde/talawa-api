[Admin Docs](/)

***

# Function: minioClient()

> **minioClient**(`fastify`): `Promise`\<`void`\>

Defined in: [src/plugins/minioClient.ts:22](https://github.com/PalisadoesFoundation/talawa-api/blob/be8575be3c5989d76dd2f84308de81461931796c/src/plugins/minioClient.ts#L22)

Integrates the talawa minio bucket name and a minio client instance on the namespaces `minio.bucketName` and `minio.client` respectively on the global fastify instance.

## Parameters

### fastify

`FastifyInstance`\<`IncomingMessage`, `ServerResponse`\>

## Returns

`Promise`\<`void`\>

## Example

```ts
import minioClientPlugin from "~src/plugins/minioClient";

fastify.register(minioClientPlugin, {});
const buckets = await fastify.minio.client.listBuckets();
```
