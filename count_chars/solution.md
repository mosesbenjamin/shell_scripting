```
#!/usr/bin/env bash

echo -n "Please insert your input"

while read line; do
    echo -n "$line" | wc -c
    echo -n "Please insert your input: "
done
```
