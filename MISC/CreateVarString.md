---
ns: MISC
---
## _CREATE_VAR_STRING

```c
// 0xFA925AC00EB830B9
long _CREATE_VAR_STRING(int flags, Any variadic);
```

```
Note: The first bit in 'flags' must not be set.
It is also required to pass at least one extra argument (this must be a text label string or hash).
When passing a hash, flags should be 0.

NativeDB Introduced: v1207
```

## Parameters
* **flags**:
* **variadic**:
