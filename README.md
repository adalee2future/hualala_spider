# 哗啦啦爬虫

通过爬虫将哗啦啦报表自动导出，以便后续数据分析

## 数据

### 哗啦啦商户中心

* 商户基本档 -> 集团菜谱 -> 门店菜谱 -> 门店菜品管理

### 哗啦啦报表中心

* 会员营销报表 -> 会员会员卡基础信息表，会员交易明细表
* 运营汇总报表 -> 订单明细查询，收银明细表
* 菜品销售报表 -> 菜品销售明细表

### 供应链

* 报表->库存报表
    * 库存 -> 库存进出明细表
    * 供应商 供应商分店表，供应商进货明细，供应商订货明细
    * 其他 库存周转明细，库存周转率

## 版本历史

* 2020-06-21 第一版本
* 2020-07-13 代码重构，以及哗啦啦网页变更引起的代码变更
* 2020-07-15 添加供应链数据
* 2020-08-24 增加爬虫失败多次尝试以及校验最终需求文件是否产生，对于目前生产环境未用到的表，都取消爬虫
