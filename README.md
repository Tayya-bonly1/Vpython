# Vpython
this like a school project of python begining
```python
import requests

url = "https://example.com/naruto_baryon_mode.png"
response = requests.get(url)

with open("naruto_baryon_mode.png", "wb") as f:
    f.write(response.content)
```
