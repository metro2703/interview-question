# Interview-Question

不定期整理一些面试题目,算是提升自己的一种途径吧!

## 最新整理

2019-03-21

> 001: 实现下面这道题目中的machine函数

```javascript
function machine() {
    
}
machine('thewall').execute() 
// start thewall
machine('thewall').do('eat').execute(); 
// start thewall
// thewall eat
machine('thewall').wait(5).do('eat').execute();
// start thewall
// wait 5s（这里等待了5s）
// thewall eat
machine('thewall').waitFirst(5).do('eat').execute();
// wait 5s
// start thewall
// thewall eat
```

欢迎在Issue区留下答案


## 历史汇总

[前端面试题及答案汇总]()