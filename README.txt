defmoulde Neo do
    #union类型
    def add(Int | Float a, Int | Float b) -> void do

    end

    #多态函数
    def sub(a) -> Int do
        Int a = 2;
        result(a);
    end

    #泛型
    assume<T>;
    def add(T a, T a) -> void do

    end 

    #泛型函数调用
    assert<Int>;
    add(a=2, b=3);

    #声明结构
    struct A do
        Int a;
        Int b;
    end

    #结构体字面量
    var b = A{a=1, b=2};

    #lambda表达式
    var a = (lambda (Int a) a);
    var c = (lambda (Int z) (+ z 1));

    def sort(a, b) -> [Int] do

    end
end
