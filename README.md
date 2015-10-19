# prcltgrep
Grep through code for module requires

## Installation

Just move this script somewhere on your `$PATH` and make sure it is executable (`chmod +x prcltgrep`)

## Usage

```bash
# Print usage
$ prctlgrep -h

# Find instances of "require('my/module')"
$ prcltgrep -m my/module

# Find instances of "require('my/module(\.js)')" 
$ prcltgrep -m my/module -e js
```
