# Minimal Maven/YAML/Scala

A minimal Maven/Scala project using [YAML polyglot](https://github.com/takari/polyglot-maven) configuration, as an alternative to heavy functional build tools like `sbt`.

```
mvnd scala:run -DmainClass="me.gladwell.test.App"  0.03s user 0.03s system 9% cpu 0.632 total

mvn scala:run -DmainClass="me.gladwell.test.App"  7.80s user 0.61s system 203% cpu 4.127 total

sbt run  15.29s user 1.33s system 205% cpu 8.094 total
```

