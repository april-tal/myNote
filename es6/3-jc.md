## es6的继承写法

- super 是处理this指向的 如果继承的话，子 类constructor内部必须添加super()
- 向super内部传参相当于向继承的父类传参
- constructor传入参数，用super接受，通过这个方式向父类传参

  ```
  class Son extends Person{
      constructor(name,firstname){
      super(firstname)
      this.name = name
    }
    jump(){
      console.log('jump')
    }
  }

  var son = new Son('hahaha','张')
  son.say()
  son.jump()
  console.log(son.name,son.firstname)
  ```
