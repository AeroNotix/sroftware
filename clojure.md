Clojure annoyances
==================

* Equality functions allow single arguments. What is the reasoning for this?
* cond allows for :else but condp doesn't.
* if-let only takes one binding form.
* The order of certain arguments is not consistent:
  * (nthafter [1 2 3 4] 2)
  * (drop 2 [1 2 3 4])
  * etc
