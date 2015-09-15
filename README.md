# TRP Module - The Sidekick to OnTrac

**T** - Third-party <br>
**R** - Regis High School <br>
**P** - Python <br>

```$ pip2 install trp```

```python
from trp import TRP
# TRP will initialize everything
t = TRP(secretsPATH, dbIP, dbPORT, dbNAME) # all arguments are optional
# TRP("./secrets.json", "localhost", "27107", "regis")  <--- defaults
t.scraper.scrape(1199, "person")
```

***secrets.json*** format:
```json
{
  "regis_username": "usernamehere",
  "regis_password": "passwordhere"
}
```
