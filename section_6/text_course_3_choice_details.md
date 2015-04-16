题目:

    var weather = "cloudy";
    var day = "sunday"
    if(weather == "cloudy")
    {
        console.log("今天的天气是多云的");
    }
    else if(day == "sunday")
    {
        console.log("今天是星期天且天气不是多云");
    }
将else if(day == "sunday")这个分支独立成 if，下面正确的是？
A.if(day == "sunday")
B.if(day == "sunday" && weather == "cloudy")
C.if(day == "sunday" && weather != "cloudy")
答案:if(day == "sunday" && weather != "cloudy")
解释: