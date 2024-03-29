# 删除资源退费

### 预付费资源 
资源删除时，若您的资源还未到期，系统会自动退还未消费部分的金额。按日按月按年付费的资源在购买时已享受周期优惠，若使用不满一个周期，将在退费时扣除优惠。

> **退款金额 = Max（0，实付订单金额 - 已消费金额）**

* 实付订单金额：用户在享受折扣后，使用现金、赠金支付的款项，不包括代金券支付的部分。
* 按日购买的资源 <br>
  当使用时长小于购买周期时：已消费金额 = 实付订单金额 ×（已使用时长 ÷ 购买周期总时长）× 1.25 <br>
  当使用时长等于购买周期时：已消费金额 = 实付订单金额
* 按月购买的资源 <br>
  当使用时长小于购买周期时：已消费金额 = 实付订单金额 ×（已使用时长 ÷ 购买周期总时长）× 1.5 <br>
  当使用时长等于购买周期时：已消费金额 = 实付订单金额
* 按年购买的资源 <br>
  当使用时长小于购买周期时：已消费金额 = 月单价 × 12 × 年数 ×（已使用时长 ÷ 购买周期总时长）<br>
  当使用时长等于购买周期时：已消费金额 = 实付订单金额
* 若已消费金额大于或等于实付订单金额，退款金额为零，欠款部分不作补收。 
* 退款金额中，购买时使用的代金券部分不支持退还，购买时使用的非代金券部分（现金/赠金）按支付比例退还。
* 退费时最小计费单位为小时，不满一小时按一小时计算。

```
例1：您购买一个月UHost，支付800元。使用10天后，删除资源进行退费，则按照退费公式进行计算：
已消费金额：800 ×（10 ÷ 30）× 1.5 = 400元
应退金额：800 - 400 = 400元
```
```
例2：您一次性购买三个月UHost，支付2400元。使用45天后，删除资源进行退费，则按照退费公式进行计算：
已消费金额：2400 ×（45 ÷ 90）× 1.5 = 1800元
应退金额：2400 - 1800 = 600元
```
```
例3：您购买一年UHost，支付8000元（月单价800元）。使用2个月后，删除资源进行退费，则按照退费公式进行计算：
已消费金额：800 × 12 × 1 ×（2 ÷ 12） = 1600元
应退金额：8000 - 1600 = 6400元
```
```
例4：您购买一年UHost，支付8000元（月单价800元）。使用11个月后，删除资源进行退费，则按照退费公式进行计算：
已消费金额：800 × 12 × 1 ×（11 ÷ 12）= 8800元
应退金额：8000 - 8800 = -800元 退款金额为0元，多出费用不额外收取
```
```
例5：您一次性购买三年UHost，支付14400元（月单价800元）。使用15个月后，删除资源进行退费，则按照退费公式进行计算：
已消费金额：800 × 12 × 3 ×（15 ÷ 36）= 12000元
应退金额：14400 - 12000 = 2400元
```

### 后付费资源 
后付费资源删除时，系统会进行自动结算，根据资源使用量收取费用。

### 特别说明
以套餐包或一次性按量形式购买的UCDN、UFile、高防、短信包等产品不进行退费。<br>
按日购买云手机，并提前释放，不作退费。<br>
购买轻量云主机退费规则：不足一天按天计算使用周期，使用部分按天1.5倍赔付，详见[轻量云主机退费细则](https://docs.ucloud.cn/ulhost/introduction/charge)<br>
购买时使用的代金券一律不支持退还。<br>
参与促销的产品，退费金额请参考具体活动规则。<br>

