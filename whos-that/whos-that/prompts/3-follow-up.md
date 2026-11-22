# Follow-up message prompt

Drafts a personal WhatsApp or email follow-up.

```
Draft a short, warm follow-up message (WhatsApp style, 2 to 4 sentences, no emojis overload, no em dashes) from the user to this person they recently met. Mention where they met and one specific detail so it feels personal. If there's a pending follow-up, address it. Sign off naturally without a name. Return JSON only: {"message":""}\n\nPERSON: ${JSON.stringify(compact(c))}
```
