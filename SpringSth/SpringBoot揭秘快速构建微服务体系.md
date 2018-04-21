<meta charset="utf-8" http-equiv="refresh" content="1">

##2.2 SpringIOC其实很简单

1. ***IOC***: Inversion Of Control  控制反转  
    1.1 ***DI***: Dependency Injection  依赖注入  
    1.2 ***DL***: Dependency Lookup     依赖查找  
    IOC就是一个先注入后查找服务的东西，然后do something  

    IOC|
    :-:|
    DI |
    DL |


2. 注册到SpringIOC容器  
    单独注册：
    ```
    < bean id="mockService" class="..mockServiceImpl">
    ```

    批量注册：
    ```
    < context :component-scan base-package="com.keevol">
    ```

##2.3 了解一点儿JavaConfig

1. 形如 *@command* 在java代码中就是JavaConfig的应用了
2. 






