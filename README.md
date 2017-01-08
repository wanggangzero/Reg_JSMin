# Reg_JSMin
One line of regular expression to delete the blank in JSON.

一行正则表达式删除JSON字符串中的所有空白字符.

 
C#
===
```
   public static string JsMin(this string str)  //  C# Extension Method
    {
        return str.RegReplace("(?<=\"|:|,|\\{|\\}|\\[|\\])\\s+(?=\"|:|,|\\{|\\}|\\[|\\]|null|\\d)", "");
    }
```



LICENSE
===
unlicense
