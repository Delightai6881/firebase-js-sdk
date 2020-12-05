<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/auth](./auth.md) &gt; [FacebookAuthProvider](./auth.facebookauthprovider.md) &gt; [credentialFromError](./auth.facebookauthprovider.credentialfromerror.md)

## FacebookAuthProvider.credentialFromError() method

Used to extract the underlying [OAuthCredential](./auth.oauthcredential.md) from a [AuthError](./auth-types.autherror.md) which was thrown during a sign-in, link, or reauthenticate operation.

<b>Signature:</b>

```typescript
static credentialFromError(error: FirebaseError): externs.OAuthCredential | null;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  error | FirebaseError |  |

<b>Returns:</b>

externs.[OAuthCredential](./auth-types.oauthcredential.md) \| null
