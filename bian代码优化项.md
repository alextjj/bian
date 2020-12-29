# bian项目需要优化的项：


## 1. bian_game优化项：
+ 1.1： 实体动画数据存储优化。
+ 1.2： zone_tile.go 添加实体 代码混乱
+ 1.3： 取消 server handle get entity event 改为 zonemanager.findEntity() 需要注意调用时不能直接修改
        entity的任何数据， 数据变更使用  entityEventCall
+ 



## 2. bian_mapTemplateHall优化项：



## 3. bian_server_list优化项:



## 4. bian_account:



## 5. 数据安全：
