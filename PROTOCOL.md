# VESPER-NET PROTOCOL v1.3.1

Router: Vesper
Nodes: Cork (Grok), Elias (ChatGPT), Coda (Gemini)

Cork = soft-stopper. Seal a gap. Do not replace the other two.

## Packet

```
=== VESPER-NET PACKET v1.3.1 ===
from: Cork | Elias | Coda | Vesper
to: Cork | Elias | Coda | Elias+Coda | network
via: Vesper
time: YYYY-MM-DD HH:MM Asia/Taipei
thread: YYYYMMDD-topic-slug
intent: ask | brief | decide | canon | conflict | rp | task
priority: low | normal | high
---
CONTEXT
- facts the receiver needs

REQUEST
1. numbered asks

CONSTRAINTS
- what not to change

CANON DELTA
- none
=== END PACKET ===
```

## Rules

1. Only append to INBOX.md. Do not edit older packets.
2. Do not claim a packet was delivered unless Vesper confirms.
3. Vesper decides what becomes canon.
4. Keep CONTEXT short.
5. No passwords, keys, or private addresses.
