<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [vue-i18n](./vue-i18n.md) &gt; [RuntimeMissingHandler](./vue-i18n.runtimemissinghandler.md)

## RuntimeMissingHandler type

<b>Signature:</b>

```typescript
export declare type RuntimeMissingHandler<Message = string> = (context: RuntimeCommonContext<Message>, locale: Locale, key: Path, type: RuntimeMissingType, ...values: unknown[]) => string | void;
```