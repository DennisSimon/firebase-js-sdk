<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/storage](./storage.md) &gt; [ListResult](./storage.listresult.md) &gt; [prefixes](./storage.listresult.prefixes.md)

## ListResult.prefixes property

References to prefixes (sub-folders). You can call list() on them to get its contents.

Folders are implicit based on '/' in the object paths. For example, if a bucket has two objects '/a/b/1' and '/a/b/2', list('/a') will return '/a/b' as a prefix.

<b>Signature:</b>

```typescript
prefixes: StorageReference[];
```