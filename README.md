## 測驗答案 

我是用javascrpit寫的 : 

1.1
```
function reverseString(string) {
    return string.split("").reverse().join("")
}
```

1.2.
```
function reverseSentence(string) {
  const sentenceArray = string.split(" ")
  return sentenceArray.map(word => word.split("").reverse().join(""))
}
```

2.
```
function howManyNum(num) {
  const numArray = []
  for(i=1;i<=num;i++>){
    if(i%15===0){}
    else if(i%3===0 || i%5===0){
      continue
    }
    numArray.push(i)
  }
  return numArray.length
}
```

3.

我會找出標示為混和的袋子
 
實際內容是 [混和] / [鉛筆] / [原子筆]
情況一:
標示顯示是 /鉛筆/   /原子筆/  /混和/
情況二:
標示顯示是 /原子筆/ /混和/    /鉛筆/

不論哪種情況都可以藉由混和的袋子推斷所有袋子的內容物
情況一: 從混和中拿出原子筆，代表這個袋子裡面確實都是原子筆
而有著鉛筆標示的袋子裡一定是混和的(因為標示都是錯誤的)
再推出剩下的一袋只能是鉛筆
情況二: 以此類推，從混和中拿出鉛筆，代表裡面真的都是鉛筆
然而原子筆標示裡面一定是混和，最後就剩原子筆


4.



