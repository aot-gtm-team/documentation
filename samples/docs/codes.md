---
sort: 3
---

# Code Blocks

`inline code`

[`inline code inside link`](#)

```
.highlight table td { padding: 5px; }
.highlight table pre { margin: 0; }
.highlight .cm {
  color: #999988;
  font-style: italic;
}
.highlight .cp {
  color: #999999;
  font-weight: bold;
}
.highlight .c1 {
  color: #999988;
  font-style: italic;
}
```

## Code highlight (css)
```css
.highlight table td { padding: 5px; }
.highlight table pre { margin: 0; }
.highlight .cm {
  color: #999988;
  font-style: italic;
}
.highlight .cp {
  color: #999999;
  font-weight: bold;
}
.highlight .c1 {
  color: #999988;
  font-style: italic;
}
```

## Code highlight (yaml)
```yaml
piVersion: v1
kind: Pod
metadata:
  labels:
  name: pod1
spec: 
  nodeSelector:
    worker: worker1
  containers:
  - image: ubi8:latest  
    name: pod1
    command:
    - sleep
    - infinity
```
