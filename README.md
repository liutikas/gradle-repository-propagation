# Propagation of plugin management added repositories

## Repro steps

1. `./gradlew lib:tasks`
2. Observe what is printed out

## Expected

```
> Configure project :lib
Repositories available:
- Google
- MavenCentral
```


## Actual

```
> Configure project :lib
Repositories available:
- Google
```