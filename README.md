# gdmetrics
dependency  of Analyzer and JInst

# Build:
```
$ mvn package
```


# Deploy to  local Maven repository 

```
$ mvn install:install-file -DgroupId=com.greenlab -DartifactId=Metrics -Dversion=1.0 -Dpackaging=jar -Dfile=target/Metrics-1.0-SNAPSHOT.jar 
```

