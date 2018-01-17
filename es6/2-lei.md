## es6 类的写法

- class内部只能写方法，并且方法之间不能加逗号
- constructor函数 当执行 new + class名 就会默认执行
- es6构造函数的写法

  ```
  class Person{
    constructor(name){
      this.name = name
    }
    say(){
      console.log('hello')
    }
  }

  let people = new Person('zhang')
  console.log(people)
  people.say()
  ```
