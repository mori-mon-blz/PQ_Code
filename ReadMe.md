## Setting

let 
  url = "https://raw.githubusercontent.com/tnclark8012/Power-BI-Desktop-Query-Extensions/master/power-query-extensions.pq"
  wc = Web.Contents(url)
in 
  Expression.Evaluate(Text.FromBinary(wc),#shared)
