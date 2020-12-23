<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [Session](./sip.js.session.md) &gt; [sessionDescriptionHandlerModifiers](./sip.js.session.sessiondescriptionhandlermodifiers.md)

## Session.sessionDescriptionHandlerModifiers property

SDH modifiers for the initial INVITE transaction.

<b>Signature:</b>

```typescript
get sessionDescriptionHandlerModifiers(): Array<SessionDescriptionHandlerModifier>;

set sessionDescriptionHandlerModifiers(modifiers: Array<SessionDescriptionHandlerModifier>);
```

## Remarks

Used in all cases when handling the initial INVITE transaction as either UAC or UAS. May be set directly at anytime. May optionally be set via constructor option. May optionally be set via options passed to Inviter.invite() or Invitation.accept().
