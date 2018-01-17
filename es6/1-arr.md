## 数组的复制

```
  let arr = [1,2,3]
  let arr1 = arr.slice(0)
  let arr1 = [...arr,4]
  arr1.push(4)
  console.log(arr,arr1)

  let name = 'lgh'
          let age = 26
          let obj = {
    name,
    age,
    say(){
      console.log(this.name);
    }
  }
  obj.say()
```
