# retailscm-biz-suite
Retail Supply Chain Management Suite




## 演示地址

https://demo.doublechaintech.com/admin/retailscm/#/home

| 角色        | 用户名           | 密码         |
| ------------- |:-------------:|:-------------------:|
|双链小超全国运营中心|SU000001|DoubleChain!y1|
|双链小超省中心|SU000002|DoubleChain!y1|
|双链小超城市服务中心|SU000003|DoubleChain!y1|
|城市合伙人|SU000004|DoubleChain!y1|
|潜在的客户|SU000005|DoubleChain!y1|
|双链小超|SU000006|DoubleChain!y1|
|生超会员|SU000007|DoubleChain!y1|
|消费者订单|SU000008|DoubleChain!y1|
|产品供应商|SU000009|DoubleChain!y1|
|供应订单|SU000010|DoubleChain!y1|
|供应订单确认|SU000011|DoubleChain!y1|
|供应订单审批|SU000012|DoubleChain!y1|
|供应订单处理|SU000013|DoubleChain!y1|
|供应货|SU000014|DoubleChain!y1|
|供应订单交货|SU000015|DoubleChain!y1|
|生超的订单|SU000016|DoubleChain!y1|
|仓库|SU000017|DoubleChain!y1|
|货架|SU000018|DoubleChain!y1|
|运输车队|SU000019|DoubleChain!y1|
|运输任务|SU000020|DoubleChain!y1|
|账套|SU000021|DoubleChain!y1|
|会计凭证|SU000022|DoubleChain!y1|
|工资等级|SU000023|DoubleChain!y1|
|员工|SU000024|DoubleChain!y1|
|用户域|SU000025|DoubleChain!y1|


## bizcore: 服务器端核心代码项目， Business Core

后端 Java/Spring/Redis/MySQL/ArrangoDB/Kafka
Java 源代码在bizcore/WEB-INF/ 下


![ScreenShot](/doc/backend.png)
````
caf_core_src: 通用框架库核心代码，包含技术框架，基础设施
caf_custom_src: 通用框架库，主要包含配置文件
retail_core_src: 零售业务核心代码
retail_custom_src: 零售业务定制代码，如果要定制，在此处增加类，继承retail_core_src的相应类，可以调用或者重写父类，core里面的类提供大量可以重用的方法。
````

## bizui：中台集成界面项目， Business UI，不是闭嘴！
前端 React/dvajs/antd/echarts/Redux


![ScreenShot](/doc/homescreen.png)
![ScreenShot](/doc/rootapp.png)

