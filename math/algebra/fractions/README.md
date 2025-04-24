# run
```
cd ~/public_github/teach/math/algebra/fractions
clj -M --main cljs.main --compile fractions.core --repl
```

try without pre call in term
M-x cider-jack-in-cljs

works both from source and REPL. But not sure if running in browser.

(js/alert "test 1")

yeah, it works. maybe use skewer to hot reload html?

(js/location.reload)

works also, hook up to f5?
