# Instructions to compile

1. ```mkdir classes``` in project root

2. ```clojure -e "(compile 'app.core)"```

3. ```clojure -A:uberjar --main-class app.core```