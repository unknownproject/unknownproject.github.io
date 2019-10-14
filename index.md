---
layout: default
---
**[Silent Hill](./silenthill.html)**
**[Indiana Jones](./indy.html)**
**[Getting Up](./indy.html)**
**[Spider-Man](./indy.html)**

```asm
PUSH ESI
CALL DWORD [<&KERNEL32.DeleteCriticalSection>]
MOV BYTE [ESI+3C],0
POP ESI
RETN
```