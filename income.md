# 客户回款

Actions
-----------------------------------------------------------------------------

### create

新建操作不支持自定义到账时间。

### update

修改操作可以调整备注和到账日期两项。到账日期发生变动后会做两件事：

1. 检查到账日期是否合法 (`Income::validateCreatedAt()`)。更改后的日期不得处于已核实的对账单区间，确保已核实的对账单准确型；
2. 同步关联余额表的创建时间字段；确保 `income.created_at` 和 `balance.created_at` 一致；

