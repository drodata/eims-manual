# 金额往来明细

Action Types
----------------------------------------------------------------------------
新增各种类型的记录及触发条件如下：

动作名称|支持修改? | 支持删除? | 路由 | 触发条件
--------|---|----|--------------------------|------------
初始化  |No | No | `seller/create`          | 新建供应商时
采购    |Yes| No | `purchase/store`         | 采购单入库 
付款    |No | No | `cost/pay-purchase`      | 支付付款申请单 
调整    |No | No | `seller/adjust-payable`  | 供应商应付、预付金额调整
代加工  |Yes| No | `oem/set-price`          | 
调配    |Yes| No | `exchange/pay`           | 调配单付款时

备注：还有个退货不再使用。
