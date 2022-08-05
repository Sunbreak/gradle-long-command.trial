- macOS/Linux

```sh
$ ./gradlew run -i > a.log
$ grep "Shortening Java classpath" a.log | wc -l
       1
```