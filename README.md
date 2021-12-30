# utilities
<i> Useful notes </i>

* Number of hours (1.5) -> time duration format ("1 h 30 min")

```
index < 1
              ? (index * 60).toInt().toString() + " min"
              : index % 1 == 0
                  ? " ${index.floor()} h"
                  : " ${index.floor()} h ${((index % 1) * 60).toInt()} min"
```
