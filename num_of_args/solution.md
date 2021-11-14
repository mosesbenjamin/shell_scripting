```
#!/usr/bin/env bash

set -eu

main () {
    case $# in
      0) printf "$s" "Usage: ./<program name> <argument>"; return 1 ;;
      1) printf "$s" "Got it: $1"; return 0 ;;
      *) return 1 ;;
    esac
}

main "$@"
```
