[JMP® 入門指南](https://www.jmp.com/zh_tw/events/ondemand/non-series/getting-started-with-jmp/watch.html#formsuccess)  
[JSL入門：從數據收集到分析自動化](https://www.jmp.com/zh_tw/events/ondemand/non-series/jsl-introduction/watch.html#formsuccess)  

- if else
	- [參考](https://community.jmp.com/t5/Discussions/How-can-I-write-a-good-condition-if-else-if-in-JMP/td-p/71032)
```
if((條件式)
  
  :     # : 為else
)
```

```
#判斷x大小
x=1;
if ((x >= 0),
	print(">=0"),
	:print("<0"),
)
```
