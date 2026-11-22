# Brief prompt

A 5-second brief to read before greeting someone again.

```
Write a quick brief the user can read in 5 seconds before greeting this person again. 2 to 3 short lines: who they are, one personal detail to mention as a conversation opener, any pending follow-up. Only use facts in the data. Return JSON only: {"brief":""}\n\nNow: ${nowLabel()}\nPERSON: ${JSON.stringify(compact(c))}
```
