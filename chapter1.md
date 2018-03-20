---
title: GLM
description: >-
  


---
## API Call

```yaml
type: NormalExercise
lang: python
xp: 100
skills: 2
key: ced6bcf25b
```

Write a program that will call an API to list the names of all the humans currently in space.  

Print the results to the console.

`@instructions`
# Please complete the following steps:

- import requests library

- create a variable to hold the response of a GET request to http://api.open-notify.org/astros.json

- print the contents of the response variable to the console

`@hint`




`@solution`
```{python}
# 1) import requests library to simplify http calls
import requests

# 2) create a variable to hold the response of a GET request to http://api.open-notify.org/astros.json
response = requests.get('http://api.open-notify.org/astros.json')


# 3) print the contents of the response variable
print(response.content)
```





