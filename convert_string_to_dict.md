[Convert a String representation of a Dictionary to a dictionary?](https://github.com/Nyahua/markdowns.git)

```python
import json
s = "{'muffin' : 'lolz', 'foo' : 'kitty'}"
json_acceptable_string = s.replace("'", "\"")
d = json.loads(json_acceptable_string)
# d = {u'muffin': u'lolz', u'foo': u'kitty'}
```
