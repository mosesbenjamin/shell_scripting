```
#!/usr/bin/env bash

arg_value=${1:-default}

if [ $arg_value = "pizza" ]; then
    echo "with pineapples?"
else
    echo "I want pizza!"
fi
```
