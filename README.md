# Second project
### Yandex Git lessons


```mermaid

    graph TD;
        untracked-->git add;
        %%git add-->staged (в списке на коммит) + tracked;
        %%staged (в списке на коммит) + tracked-->git commit;
        %%git commit-->tracked;
        %%tracked-->изменения;
        %%изменения-->modified;
        %%modified-->git add;
        %%git add-->staged (в списке на коммит) + tracked;
```
