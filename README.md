# Second project
### Yandex Git lessons


```mermaid

    graph TD;
        U[untracked]-->GA[git add];
        GA-->S[staged <br> (в списке на коммит) <br> + tracked]-->GC[git commit];
        GC-->T[tracked];
        T-->CH[изменения];
        CH-->M[modified];
        M-->GAA[git add];
        GAA-->S;
```
