# 订单

操作列表
---------------------------------------------------------------------------

### 作废

评审完成的订单原则上不再支持删除操作，可以通过“作废”操作将订单状态设置为“已作废”。

当同时满足一下条件时，销售员可以进行“作废”操作：

1. 订单状态是“准备中”（即没有交付过）；
2. 订单没有任何取料记录；
3. 订单没有任何采购记录；

评审顺序：销售经理、仓管员、生产经理。评审通过后，如果订单之前为“已付款”，系统将删除对应的余额变动记录。
