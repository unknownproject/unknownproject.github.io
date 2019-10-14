---
layout: default
---

**[[ Silent Hill ]](./silenthill.html)**
**[[ Indiana Jones ]](./indy.html)**
**[[ Getting Up ]](./gettingup.html)**
**[[ Spider-Man ]](./spiderman.html)**

```asm
CALL DWORD PTR DS:[<&MSVCR80._aligned_free>]
ADD ESP,4
MOV ECX,EDI
MOV DWORD PTR SS:[LOCAL.0],-1
CALL 1001AF14
POP EDI
MOV ECX,DWORD PTR SS:[LOCAL.2]
POP ESI
MOV DWORD PTR FS:[0],ECX
ADD ESP,10
RETN
```

