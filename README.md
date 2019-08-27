Build and run:

```
xbuild /p:Configuration=Debug /p:TargetFrameworkVersion=v4.5 &&
mono ConsoleApplication1/bin/Debug/ConsoleApplication1.exe
```

Reviewing code and trying to replicate the comparisons between the Valiant and greedy attacks. Uncommented `depthExperiment3` in `main` to compare Valiant in `BestDepthReducingSetExcludeGreedy` with `myGreedyDRSetsApxNoSortingNew`.
