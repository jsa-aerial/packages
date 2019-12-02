# cljsjs/heatmapjs

[](dependency)
```clojure
[cljsjs/heatmapjs "2.0.5-0"] ;; latest release
```
[](/dependency)

This jar comes with `deps.cljs` as used by the [Foreign Libs][flibs] feature
of the ClojureScript compiler. After adding the above dependency to your project
you can require and use the packaged library like so:

```clojure
(ns application.core
  (:require cljsjs.heatmapjs))

```

Externs were generated using https://github.com/jmmk/javascript-externs-generator and handwritten.
[flibs]: https://clojurescript.org/reference/packaging-foreign-deps