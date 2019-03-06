# IPMap
## Who's knocking?

After noticing tons of failed SSH login attempts to my home computer,
I thought it'd be interesting to try to build a heatmap of where they're
coming from.

This module uses geoip2 to geolocate the IP addresses, and then uses
Matplotlib to plot those locations.

### Dependencies
```geoip2``` package in python, available through ```pip```
