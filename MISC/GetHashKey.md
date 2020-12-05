---
ns: MISC
---
## GET_HASH_KEY

```c
// 0xFD340785ADF8CFB7 0x98EFF6F1
Hash GET_HASH_KEY(char* string);
```

```
Computes a hash for the given string. It is hashed using Jenkins' One-at-a-Time hash algorithm (https://en.wikipedia.org/wiki/Jenkins_hash_function)
Note: this implementation is case-insensitive.

NativeDB Introduced: v1207
```

## Parameters
* **string**:
