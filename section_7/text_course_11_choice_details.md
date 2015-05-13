题目: 
    var person={fname:"Bill",lname:"Gates",age:56};
    var x;
    var txt = ""
    for ( x in person)
    {
        txt = txt + person[x];
    }
    console.log(txt);
打印结果为
A.BillGates56
B.fname:BilllnameGatesage
答案:BillGates56
解释:
