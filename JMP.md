[JMP® 入門指南](https://www.jmp.com/zh_tw/events/ondemand/non-series/getting-started-with-jmp/watch.html#formsuccess)  
[JSL入門：從數據收集到分析自動化](https://www.jmp.com/zh_tw/events/ondemand/non-series/jsl-introduction/watch.html#formsuccess)  

[SAS程式語言](https://www.diklearn.com/a/202101/58525.html)  
```
#生成資料集 命名為out1，
也可以省略資料集名，這時sas自動生成一個臨時資料集名。
也可以使用特殊名字_null_ ，表示本資料步不生成資料集。
data out1;
```

- 賦值語句
```
#用賦值語句計算一個值並存放到變數中
avg = (math + chinese)/2;

isfem = (***='女');

y=sin(x)**2;

newv = .;

第一個賦值語句用一個公式計算平均分數。
第二個生成一個取值為0或1的變數，性別為女時為1，否則為0。
第三個使用了正弦函式和乘方運算。
第四個給變數賦了缺失值。
```

- 輸出語句
  - put
```
data;

x=0.5;

y=sin(x);

put 'sine function value of ' x 'is ' y;

run;
```
顯示結果  
```
sine function value of 0.5 is 0.4794255386
```
    - 顯示帶有變數名的輸出結果
```
put x= y=;
```
顯示結果  
```
x=0.5 y=0.4794255386
```
 
