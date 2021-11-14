```
#!/usr/bin/env bash

re='^[0-9]+$'

if ![[ $1 =~ $re && $2 =~ $re ]]; then
    echo "Input two numbers.."
    exit 2
fi

function sum {
    exho $(( $1 + $2 ))
}

sum $1 $2
```
