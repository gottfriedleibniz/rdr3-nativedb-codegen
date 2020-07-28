---
ns: NETWORK
---
## _GET_DATE_AND_TIME_FROM_UNIX_EPOCH

```c
// 0xAC97AF97FA68E5D5 0xBB7CCE49
void _GET_DATE_AND_TIME_FROM_UNIX_EPOCH(int unixEpoch, Any* timeStructure);
```

```
Takes the specified time and writes it to the structure specified in the second argument.

struct date_time
{
    int year;
    int PADDING1;
    int month;
    int PADDING2;
    int day;
    int PADDING3;
    int hour;
    int PADDING4;
    int minute;
    int PADDING5;
    int second;
    int PADDING6;
};
```

## Parameters
* **unixEpoch**:
* **timeStructure**:
