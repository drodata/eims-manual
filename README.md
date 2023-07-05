# 订单系统操作手册

变更日志
-------------------------------------------------------------------------

时间        | 大类  | 动作  | 说明
------------|-------|-------|-------
2023-07-05  | 订单  | 新增  | [终止交付操作][deal-terminate] (制品)
2023-07-01  | 生产  | 新增  | [砂轮压块异常上报][gwp-press-lapse]
2023-06-28  | 物资  | 新增  | [消耗品领用][material-requisition]
2023-06-20  | 订单  | 新增  | [作废操作][order-discard]
2023-06-09  | 订单  | 新增  | [取料建议评审][order-selection-pick-suggestion]
2023-06-06  | 生产  | 新增  | 砂轮生产增加[过程追溯功能][gwp-trace]
2023-05-29  | 采购  | 新增  | 采购清单[标记已完成][demand-item-mark-completed]
2023-05-27  | 采购  | 新增  | [采购清单][demand-item]延期操作
2023-05-22  | 订单  | 新增  | 分批交付的订单支持[终止交付][order-end]操作
2023-05-20  | 订单  | 新增  | 申请过备货的客户,新建订单后增加[匹配备货][order-match-hoard]操作
2023-05-09  | 销售  | 新增  | [客户备货][customer-hoard]

[deal-terminate]: deal/deal.md#zhong-zhi-jiao-fu
[material-requisition]: material/requisition.md
[customer-hoard]: customer/hoard.md
[order-discard]: order/order.md#zuo-fei
[order-end]: order/end.md
[order-match-hoard]: order/match-hoard.md
[demand-item]: purchasing/demand-item.md
[demand-item-mark-completed]: purchasing/demand-item.md#biao-ji-yi-wan-cheng
[gwp-trace]: grinding-wheel-production/trace.md
[gwp-press-lapse]: grinding-wheel-production/press.md#yi-chang-shang-bao
[order-selection-pick-suggestion]: order/selection.md#qu-liao-jian-yi
