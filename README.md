### key-project
---
https://dl.bintray.com/key/stable-snapshots/

https://www.key-project.org/

```java
private void mergeCollapse() {
  while (stackSize > 1) {
    int n = stackSize - 2;
    if (n > 0 && runLen[n-1] <= runLen[n] + runLen[n+1]) {
      if (runLen[n - 1] < runLen[n + 1])
        n--;
      mergeAt(n);
    } else if (runLen[n] <= runLen[n + 1]) {
      mergeAt(n);
    } else {
      break;
    }
  }
}
```

```
```

```
```
