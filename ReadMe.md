## Setting

```pq
let 
  url = "https://raw.githubusercontent.com/mori-mon-blz/PQ_Code/refs/heads/main/Functions.pq"
  wc = Web.Contents(url)
in 
  Expression.Evaluate(Text.FromBinary(wc),#shared)
```
