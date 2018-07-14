# OneBillion

基于星云链的目标激励平台，通过星云币激励用户养成良好的计划习惯。

## 功能介绍
目标激励计划有以下两种：

### Plan A

此计划的设计初衷是在于培养用户的自觉性，通过每天签到最后完成计划一次性获得奖励的形式，让用户体验坚持的愉悦与成功的快感。
* 首先需要用户设置计划的持续时间和每天投入的金额；
* 用户需每天向合约发起一笔交易进行签到，同时每天向合约转入一定金额；
* 当计划时间到后，根据用户签到情况返回部分或者全部投入金额；
* 此外，如果签到情况优秀，还会获得额外奖励；
* 整个计划使用星云币进行激励或惩罚的形式让用户培养出坚持的好习惯。

### Plan B

Plan B与Plan A相反，一次性投入一定量星云币，然后每天签到就给与奖励，连续签到奖励更多 (此处奖励都是用户最开始投入的星云币，并非合约预先存入)。具体的运作原理如下：

* 首先用户需要设定创建计划时初始投入的金额以及计划持续的时间；
* 调用合约并向合约转入上述填入的金额进行创建新计划；
* 用户每天签到，合约都会向用户返回一定量金额（具体根据用户初始存入金额计算）；
* 合约向用户返回的金额是根据用户初始投入的金额构成的等差数列，连续签到会在前一天的奖励之上再加额外的奖励；如果用户断签，奖励金额回归到等差数列初始值；
* 此计划希望通过每天持续的奖励、连续签到奖励更多的形式，通过奖励激发用户的行动力。


# 获奖

此项目连续获得星云链第一季激励计划2nd week、3rd week优秀项目奖。

详情可参见：https://incentive.nebulas.io/dapps-board.html
