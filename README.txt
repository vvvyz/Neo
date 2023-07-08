(defmoudle Neo

    (define add
        (fun ([:x Int] [:b Int] [-> Int])
            (define c (+ a b))
            (Result c)))

    (assume T)
    (define add
        (func ([:a T] [-> Int])))
)
