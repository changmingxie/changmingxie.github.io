# 术语

## 领域对象
具有唯一标识，一般与数据库持久化对象存在一对一的关系。依附于聚合根，生命周期由聚合根统一管理。  

## 聚合根
聚合根是一种特殊的领域对象，具有全局唯一标识，有独立的生命周期，聚合根在聚合内对领域对象采用直接引用的方式进行组织和协调。

## 领域事件
发生在一个领域中，但被其他领域所关注的事件，用于降低不同领域间的耦合性。

## domain
domain要保证唯一性，一般与服务一一对应，主要用于对事件隔离。   