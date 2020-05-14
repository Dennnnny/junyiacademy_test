## 測驗答案 

我是用javascrpit寫的 : 

1.
```
function reverseString(string) {
    return string.split("").reverse().join("")
}
```

2.
```
function reverseSentence(string) {
  const sentenceArray = string.split(" ")
  return sentenceArray.map(word => word.split("").reverse().join(""))
}
```

3.
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