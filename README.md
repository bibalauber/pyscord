# pyscord
A simple python library to interact with the discord api

# Documentation

##   The 'User' object
A basic example to get the user informations

```python
import pyscord

user = User("<token>")
print(user.userInfo("<userid>")
```

### Additional parameters
- ``response``: Modify the response format. 2 options, ``simple`` more simple but not with all the infos and ``raw`` is the raw response from the discord api
