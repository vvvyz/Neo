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
    def add[T](T a, T a) -> void do

    end 

    #泛型函数调用
    add[Int](a=2, b=3)

    #声明结构
    struct A do
        Int a;
        Int b;
    end

    #结构体字面量
    var b = A{a: 1, b: 2};

    #lambda表达式
    var a = \x -> x;
end
