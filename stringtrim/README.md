This plugin provides a payload generator for Intruder which will trim off one character at a time from the right side of a given position.  I don't really have any particular use case in mind, but I wrote it in an attempt to determine what sort of structure some encrypted data might have by removing one character at a time and seeing what errors appear.

To paraphrase a conversation from Van Helsing:
```
Van Helsing: Seven years and you don't know what it does?

Carl: I didn't say that. I said I don't know what it's for, what it does is [trim off one character at a time from the right side of a given position].
```

Anyway, it requires JPython so make sure you have that configured in Burp.