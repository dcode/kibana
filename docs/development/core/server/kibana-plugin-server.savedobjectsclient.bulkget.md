<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-server](./kibana-plugin-server.md) &gt; [SavedObjectsClient](./kibana-plugin-server.savedobjectsclient.md) &gt; [bulkGet](./kibana-plugin-server.savedobjectsclient.bulkget.md)

## SavedObjectsClient.bulkGet() method

Returns an array of objects by id

<b>Signature:</b>

```typescript
bulkGet<T extends SavedObjectAttributes = any>(objects?: SavedObjectsBulkGetObject[], options?: SavedObjectsBaseOptions): Promise<SavedObjectsBulkResponse<T>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  objects | <code>SavedObjectsBulkGetObject[]</code> | an array of ids, or an array of objects containing id, type and optionally fields |
|  options | <code>SavedObjectsBaseOptions</code> |  |

<b>Returns:</b>

`Promise<SavedObjectsBulkResponse<T>>`

## Example

bulkGet(\[ { id: 'one', type: 'config' }<!-- -->, { id: 'foo', type: 'index-pattern' } \])

