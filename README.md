# dingtalkmsgsync
钉钉聊天消息同步数据库进行统计分析，支持多群监控，参考https://github.com/gongxi-cn-ln-dl/DingTalk，https://github.com/Macfee/DingDing-Web

## 运行效果结果
```sh
******************************
{'运维平台告警群'} 最后一条消息： {'message': ["text:[ecrmupgrade]-[srm:980199]-[运维平台升级告警] 开始任务：kdemo;版本 3.00;操作 upgrade;相关模块 ['kylin_base', 'kylin_ccms', 'kylin_loyalty', 'kylin_ebm', 'kylin_benefit', 'kylin_cdp', 'kylin_ebrand', 'kylin_content', 'kylin_center', 'kylin_quickcovent', 'kylin_newbi']@26963755 @7985002 "], 'timestamp': 1661493261832, 'openId': 2724327393}
{'售后技术运维'} 最后一条消息： {'message': ['text:没有'], 'timestamp': 1661493858629, 'openId': 7985002}
******************************
{'运维平台告警群'} 最后一条消息： {'message': ["text:[ecrmupgrade]-[srm:980199]-[运维平台升级告警] 开始任务：kdemo;版本 3.00;操作 upgrade;相关模块 ['kylin_base', 'kylin_ccms', 'kylin_loyalty', 'kylin_ebm', 'kylin_benefit', 'kylin_cdp', 'kylin_ebrand', 'kylin_content', 'kylin_center', 'kylin_quickcovent', 'kylin_newbi']@26963755 @7985002 "], 'timestamp': 1661493261832, 'openId': 2724327393}
{'售后技术运维'} 最后一条消息： {'message': ['text:没有'], 'timestamp': 1661493858629, 'openId': 7985002}
******************************
来自<运维平台告警群>新消息>>> {'message': ['text:[ecrmupgrade]-[srm:980199]-[运维平台升级告警] 当前升级任务超时: domain-kdemo;task_id-46ebfee0929caefa943a2b0ec54e484e;更新时间-2022-08-26 13:54:19.368284@26963755 @7985002 '], 'timestamp': 1661493968929, 'openId': 2724327393}
{'运维平台告警群'} 最后一条消息： {'message': ['text:[ecrmupgrade]-[srm:980199]-[运维平台升级告警] 当前升级任务超时: domain-kdemo;task_id-46ebfee0929caefa943a2b0ec54e484e;更新时间-2022-08-26 13:54:19.368284@26963755 @7985002 '], 'timestamp': 1661493968929, 'openId': 2724327393}
******************************
{'售后技术运维'} 最后一条消息： {'message': ['text:没有'], 'timestamp': 1661493858629, 'openId': 7985002}
{'运维平台告警群'} 最后一条消息： {'message': ['text:[ecrmupgrade]-[srm:980199]-[运维平台升级告警] 当前升级任务超时: domain-kdemo;task_id-46ebfee0929caefa943a2b0ec54e484e;更新时间-2022-08-26 13:54:19.368284@26963755 @7985002 '], 'timestamp': 1661493968929, 'openId': 2724327393}
******************************
{'售后技术运维'} 最后一条消息： {'message': ['text:没有'], 'timestamp': 1661493858629, 'openId': 7985002}

```
