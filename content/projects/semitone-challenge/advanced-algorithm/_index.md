---
_db_id: 197
content_type: project
flavours:
- javascript
- typescript
from_repo: projects/semitone-challenge/basic-algorithm
pre: <b>3. </b>
prerequisites:
  hard:
  - projects/semitone-challenge/basic-algorithm
  soft: []
ready: true
submission_type: continue_repo
title: semitone difference - Advanced algorithm
weight: 3
tags:
- problem solving
---

Adjust your `JamBuddy` class so that it can handle flats and sharps.

Here is an example usage:

JS:

```
let buddy = new JamBuddy()
let notes = buddy.selectNotes()
console.log(notes) # let's pretend that this outputs ['A#', 'Db']

let correct = buddy.checkAnswer(1)
console.log(correct) # false

correct = buddy.checkAnswer(3)
console.log(correct) # true
```

Have fun :)

## Acceptance criteria

The usual. TDD is a must