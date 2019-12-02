<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-public](./kibana-plugin-public.md) &gt; [HttpInterceptor](./kibana-plugin-public.httpinterceptor.md) &gt; [requestError](./kibana-plugin-public.httpinterceptor.requesterror.md)

## HttpInterceptor.requestError() method

Define an interceptor to be executed if a request interceptor throws an error or returns a rejected Promise.

<b>Signature:</b>

```typescript
requestError?(httpErrorRequest: HttpErrorRequest, controller: IHttpInterceptController): Promise<Request> | Request | void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  httpErrorRequest | <code>HttpErrorRequest</code> |  |
|  controller | <code>IHttpInterceptController</code> |  |

<b>Returns:</b>

`Promise<Request> | Request | void`
