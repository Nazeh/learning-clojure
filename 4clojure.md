things I learned from 4 clojure


lists, vectors, and sets can be created from each other!

Conj add items to the start of Lists, and to the end of Vectors.

sets, and maps don't need escaping because they can't be confused with syntax??

sequences are like enumerables in ruby?

ways to create fn
  (fn name [x] (+ x 5))
  (fn [x] (+ x 5))
  #(+ % 5)
  (partial + 5)
