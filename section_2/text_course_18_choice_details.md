题目: 请选出正确的打印结果

    var a;
    function fun() {
        a = 1;
    }
    fun()
    console.log(a)
A.undefined
B.1
答案:1
解释: 按照作用域的定义，子作用域可以访问父作用域的变量，所以执行完函数后，a就被赋值为1了