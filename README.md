# snippets
A few snippets that i use in almost all of my projects
## Python
logging
```py
import loguru
logger.remove()
logger.add(
    sys.stdout,
    colorize=True,
    format="[ <lr>bfportal</> ]"
    "[<b><fg #3b3b3b>{level: ^8}</></>]"
    "[{name}.{function}:{line}]"
    "[ {message} ]",
    level="DEBUG",
)
```
