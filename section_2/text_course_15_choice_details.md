题目:

    var a = '1';
    var a; console.log(a)
的输出结果为
A.undefined
B.nil
C.1
答案:1
解释: 这是js里比较诡异的地方，一旦一个变量被声明过，再次声明不会报错也不会清除之前的值。好孩子不要这么干。