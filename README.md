# prcltgrep
Grep through code for module requires

## Usage

```bash
# Print usage
$ prctlgrep -h

# Find instances of "require('my/module')"
$ prcltgrep -m my/module

# Find instances of "require('my/module(\.js)')" 
$ prcltgrep -m my/module -e js
```
