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
解释: