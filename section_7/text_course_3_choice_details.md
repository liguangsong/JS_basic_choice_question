题目:

    var array = [1,2,3,4];
    for (var i = 0; i < array.length; i ++)
    {
        if(i < 2)
        {
            continue;
        }
        console.log(array[i]);
    }
打印结果是什么？
A.0,1
B.1,2,3,4
C.1,2
D.3,4
E.2,3,4
答案:3,4
解释: