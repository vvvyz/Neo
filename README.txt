(defmoudle Neo
    (define add
        (lambda ([:x Int] [:b Int] [-> Int])
            (define c (+ a b))
            (Result c)
        )
    )

    (assume T)
    (define add
        (lambda ([:a T] [-> Int])
            )
        )
)
