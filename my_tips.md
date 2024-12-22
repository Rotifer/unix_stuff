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

- Use the _seq_ command to generate a series of numbers

```sh
# You don't. Use e.g. seq for that, because brace expansion is performed before any other expansions and eval is evil :-)

a=5

seq 1 $a
```
- Get the type of a file with the _file_ command

```sh
file epl # Returns: epl: DuckDB database file, version 64
```


