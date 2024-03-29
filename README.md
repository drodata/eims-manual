# 订单系统操作手册

变更日志
-------------------------------------------------------------------------

- 2023-08-14  采购 `调整` 不合格品让步接收[增加评审环节][purchasing-purchase-decision]
- 2023-08-11  采购 `调整` [采购员可以快速完成普通商品的检测][purchasing-purchase-inspection]
- 2023-08-05  采购 `新增` [留样][purchasing-purchase-specimen]
- 2023-08-02  物资 `新增` [台帐一致性审核][material-requisition-review]
- 2023-07-22  生产 `新增` [混料阶段数量异常上报][gwp-mix-lapse]
- 2023-07-21  生产 `新增` [原辅料数量变动日志][gwp-trace-snap]
- 2023-07-07  物资 `新增` [领料申请单][material-bucket]
- 2023-07-05  订单 `新增` [终止交付操作][deal-terminate] (制品)
- 2023-07-01  生产 `新增` [砂轮压块异常上报][gwp-press-lapse]
- 2023-06-28  物资 `新增` [消耗品领用][material-requisition]
- 2023-06-20  订单 `新增` [作废操作][order-discard]
- 2023-06-09  订单 `新增` [取料建议评审][order-selection-pick-suggestion]
- 2023-06-06  生产 `新增` 砂轮生产增加[过程追溯功能][gwp-trace]
- 2023-05-29  采购 `新增` 采购清单[标记已完成][demand-item-mark-completed]
- 2023-05-27  采购 `新增` [采购清单][demand-item]延期操作
- 2023-05-22  订单 `新增` 分批交付的订单支持[终止交付][order-end]操作
- 2023-05-20  订单 `新增` 申请过备货的客户,新建订单后增加[匹配备货][order-match-hoard]操作
- 2023-05-09  销售 `新增` [客户备货][customer-hoard]

[deal-terminate]: deal/deal.md#zhong-zhi-jiao-fu
[material-bucket]: material/bucket.md
[material-requisition]: material/requisition.md
[material-requisition-review]: material/requisition.md#tai-zhang-yi-zhi-xing-shen-he
[customer-hoard]: customer/hoard.md
[order-discard]: order/order.md#zuo-fei
[order-end]: order/end.md
[order-match-hoard]: order/match-hoard.md
[demand-item]: purchasing/demand-item.md
[demand-item-mark-completed]: purchasing/demand-item.md#biao-ji-yi-wan-cheng
[purchasing-purchase-inspection]: purchasing/purchase.md#jian-ce
[purchasing-purchase-specimen]: purchasing/purchase.md#liu-yang
[purchasing-purchase-decision]: purchasing/purchase.md#bu-he-ge-pin-chu-li
[gwp-mix-lapse]: grinding-wheel-production/mix.md#yi-chang-shang-bao
[gwp-trace]: grinding-wheel-production/trace.md
[gwp-trace-snap]: grinding-wheel-production/trace.md#shu-liang-bian-dong-ri-zhi
[gwp-press-lapse]: grinding-wheel-production/press.md#yi-chang-shang-bao
[order-selection-pick-suggestion]: order/selection.md#qu-liao-jian-yi
