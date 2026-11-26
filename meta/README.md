| 字段名称     | 字段含义                                   | 可选值                              | 说明                                          |
| ------------ | ------------------------------------------ | ----------------------------------- | --------------------------------------------- |
| ID           | 触发器ID                                   | 英文字符串                          |                                               |
| Name         | 触发器名称                                 | 英文字符串                          |                                               |
| TeamID       | 生成的队伍ID                               | 英文字符串                          |                                               |
| Owner        | 可以使用此触发器的国家                     | 国家名称、all                       | all代表所有国家                               |
| TechLevel    | 科技等级                                   | 数字                                |                                               |
| CondType     | 条件类型                                   | self、enemy                         | self表示此条件检测己方单位，enemy检测地方单位 |
| CondObject   | 条件对象                                   | 建筑/单位名称                       |                                               |
| ObjectCount  | 对象数量                                   | 数字                                |                                               |
| CondOperator | 条件操作符                                 | eq、lt、gt、le、ge                  | 等于、小于、大于、小于等于、大于等于          |
| WeightInit   | 初始权重                                   | 数字、rand                          | rand表示随机生成一个10~1000的数字             |
| WeightMin    | 最小权重                                   | 数字、rand                          |                                               |
| WeightMax    | 最大权重                                   | 数字、rand                          |                                               |
| EnableMode   | 启用模式，控制触发器可以在哪些模式下使用   | bat、oth                            | 战役模式、其他模式(包括遭遇战)                |
| PlaceHolder1 | 占位符，无效                               |                                     |                                               |
| Camp         | 阵营，只有在此阵营下的国家才能使用此触发器 | allied、soviet、yuri、4th、5th、6th | 4th、5th、6th用于兼容其他阵营                 |
| PlaceHolder2 | 占位符，无效                               |                                     |                                               |
| EnableEasy   | 是否在简单模式启用                         | yes、no                             |                                               |
| EnableNorm   | 是否在普通模式启用                         | yes、no                             |                                               |
| EnableHard   | 是否在困难模式启用                         | yes、no                             |                                               |

