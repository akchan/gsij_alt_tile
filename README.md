# gsij_alt_tile

python library for altitude tile system of the Geospatial Information Authority of Japan

## Usage

```py
from gsij_alt_tile import GsijAltTile

zoom = 14
longitude = 140.0
latitude = 35.0

gat = GsijAltTile(zoom=zoom)

alt_m = gat.get_alt(longitude, latitude)

print('Altitude (m):', alt_m)
```
