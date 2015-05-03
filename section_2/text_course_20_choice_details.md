题目: 请选出正确的打印结果

    var a = 1;
    fun();
    function fun() {
        console.log(a);
        var a = 2;
    }
    console.log(a);

A.undefined 2
B.undefined 1
C.1 2
D.1 1
答案:undefined 1
解释:js比较诡异的地方就在这里了，经常被人吐槽。因为我们在fun里面定义了重名的变量a。但是它不是当声明的时候才覆盖掉父作用域的变量，而是只要有就覆盖掉了，所以在声明之前打印就是undefined。总之，不要随便起重名的变量名。希望我们永远不要用到这个知识。