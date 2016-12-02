# reminder

> Reminder app

### Compile

```
$ erl -make
```

### Start

```
$ erl -pa ebin/
```

### Load from shell


```
$ make:all([load]).
```

Looks for a file named Emakefile in current dir, recompiles it (if it changed), and loads the new files.
