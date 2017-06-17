# empty-scala-project

# install + run (spacemacs)

using ensime, e.g. as a [spacemacs layer](https://github.com/syl20bnr/spacemacs/tree/master/layers/%2Blang/scala)?

```
sbt ensimeConfig 
sbt ensimeConfigProject
```

now go to a `src/main/scala/example/Hello.scala`
and do `SPC m b r` to run, or `SPC m b c` to compile.

see [full Scala layer](https://github.com/syl20bnr/spacemacs/tree/master/layers/%2Blang/scala) for more

# install + run (regular / sbt)

```
kd bluebird
sbt
> run
```


