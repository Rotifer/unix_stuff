# My tips

Notes and code snippents on unix/linux stuff including unix commands and tools and shell scripting

* Using _curl_ to get a weather report (works on OS X)

```{console}
curl https://v2.wttr.in/London
```

* Delete all empty files in the current directory

```{console}
find . -size  0 -print -delete
```

* Kill a specific port

For example, MySQL running on 3306

```{console}
kill $(lsof -t -i:3306)
```




