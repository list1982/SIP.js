<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [Dialog](./sip.js.dialog.md) &gt; [initialDialogStateForUserAgentClient](./sip.js.dialog.initialdialogstateforuseragentclient.md)

## Dialog.initialDialogStateForUserAgentClient() method

When a UAC receives a response that establishes a dialog, it constructs the state of the dialog. This state MUST be maintained for the duration of the dialog. https://tools.ietf.org/html/rfc3261\#section-12.1.2

<b>Signature:</b>

```typescript
static initialDialogStateForUserAgentClient(outgoingRequestMessage: OutgoingRequestMessage, incomingResponseMessage: IncomingResponseMessage): DialogState;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  outgoingRequestMessage | <code>OutgoingRequestMessage</code> | Outgoing request message for dialog. |
|  incomingResponseMessage | <code>IncomingResponseMessage</code> | Incoming response message creating dialog. |

<b>Returns:</b>

`DialogState`
