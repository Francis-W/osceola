# osceola
an IOC framework for function programming

## Introduction
osceola is an idea to manage functions with IOC model.
if someone write an function and regist it to framework. the framwork can manage functions and it's output result
so when some function use some prev-result of other function, framework can use DI inject prev-result into it.

## Something interesting
1. by IOC we can make an decoupling between functions.
2. by lazy function we can combine functions into an big and complex function,and then run it in an seprate thread
3. framwork can combine with an cache library. so result of functions can expand to bigger space.
4. famework can make an refrence-count of each function. clean functions let JVM unload class refrence
