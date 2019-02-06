# ibazel

```
ibazel build :app
# 87s
```

Update in `package0/timer0.ts` takes extra 84s to recompile.


# tsc

```
tsc -w
# 20s
```

Update in `package0/timer0.ts` takes milliseconds.

