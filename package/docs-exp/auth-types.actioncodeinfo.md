<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/auth-types](./auth-types.md) &gt; [ActionCodeInfo](./auth-types.actioncodeinfo.md)

## ActionCodeInfo interface

A response from [checkActionCode()](./auth.checkactioncode.md)<!-- -->.

<b>Signature:</b>

```typescript
export interface ActionCodeInfo 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [data](./auth-types.actioncodeinfo.data.md) | { email?: string \| null; multiFactorInfo?: [MultiFactorInfo](./auth-types.multifactorinfo.md) \| null; previousEmail?: string \| null; } | The data associated with the action code. |
|  [operation](./auth-types.actioncodeinfo.operation.md) | [Operation](./auth-types.operation.md) | The type of operation that generated the action code. |
