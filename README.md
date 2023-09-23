# Second project
### Yandex Git lessons


```mermaid

    graph TD;
        A[untracked]-->B[git add];
        B-->C[staged <br> (в списке на коммит) <br> + tracked]-->D[git commit];
        D-->E[tracked];
        E-->F[изменения];
        F-->G[modified];
        G-->H[git add];
        H-->C;
```
