# Indonesian-geojson

For simple usage in python we can use `urllib library` and `json library` as below:

```
from urllib.request import urlopen
import json

response = urlopen('https://raw.githubusercontent.com/wowothk/indonesian-geojson/main/kabkot_bali.json')
json.loads(response.read())
```
