# tor-login-faker

Posts fake unique login information to a fake website through all possible tor exit nodes, and later waits for login attempt with these unique credentials and detects which exit node that sniffed the traffic

Written for use on Linux, does not currently work correctly on Windows

## Requirements

- requests, pysocks and stem, can be installed using "pip install requests stem pysocks"
- Python 3 (currently, might change)

## Thanks to

@intchloe idea and base [Don't touch my binary](https://github.com/intchloe/Don-t-touch-my-bin-/)