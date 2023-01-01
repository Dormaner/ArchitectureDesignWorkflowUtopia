# 建筑设计流程乌托邦

此为一个思想实验，尝试构想出一个完美的建筑设计工作流程，以这个流程为基础判断各个软件的职能与优劣情况，甚至可以成为流程中某款软件的设计参考。

## 指导思想

不以优化现有方案为思考角度。而尝试着构建一个`完美`的方案，再反观现有方案给出对现有方案的优化策略。

## 变量与不变量

为了达到上述要求，需要确认什么是现有方案中`不可变的`，而什么又是`可变的`或者说`可以忽略的`。有了这个条件后就可以在不违反不变量的情况下，尽可能地分析出最优方案。

### 不变量

- 工作流程的结果——一套可以指导施工的`数据文件`。
- 人的限制——人的记忆力与学习力是`有限`的。
- 建筑设计的内容与思考范围是`日益增加`的。
- 某些必要的`法律法规`。

### 变量

- 工作流程结果的`形式`，可是图纸集、三维模型或任何数据类型可以指导施工的。
- 工作流程的阶段。
- 工作流程各个人员的`角色`或`职能`。

## 工作流

思考在整个工作流程中，从刚刚开始到完成施工指导文件，思考以下问题：

- 一共有多少阶段以及有多少不同职能的人员
- 不同阶段之间界定的标准
- 不同职能人员的`职能范围`
- 不同职能人员在不同阶段所需完成的`任务`
- 不同职能人员所需`参与`的阶段

### 最优评判标准

比较难通过一个准确的量化标准去评判一个工作流程的优秀与否。

但是可以从如下几个角度来思考工作流是否有优化空间。

- 减少人员交流成本

  - 不同角色或职能的人员之间所需`交流内容量`是否能减少。

  - 不同角色或职能的人员之间交流的`链接网`是否可以`更简`。

- 人员工作内容的分配均匀问题

  - 在同一个阶段内，不同职能之间的人员的工作量是否`均匀`。
  - 同一个职能的人员参与工作流程的阶段是否是`连续`的。

## 工具设计

某个职能人员在某个阶段所需解决的问题中，所需要使用的工具应该是什么样的。

- 工具的形式
- 交互的方法
- 数据的传输
- 解决的问题

暂时不考虑技术实现的具体方法，只需要估计大概在十年内技术难题是可攻破的，不需要具体论证。

主要考虑`表现形式`、`交互形式`、`交流模式`等，进行宏观性思考，证明从宏观层面上，最优的。

### 最优评判标准

总体来说工具的作用是让使用者提高工作的效率与质量。 

- 质量
  - 是否能降低工作者的`出错率`
  - 提高了成品的`品质上限`
- 效率
  - 是否提升了使用者从构思到生成所需数据的效率——`交互`
  - 是否提升了数据生成的效率——`生成/辅助`

## 思考结果

一定是一个完整的工作流程，包括如下要素。

- 包含不同设计人员的职能描述以及不同阶段的`任务`。
- 包含不同阶段各个人员所需要的数据和结果数据的`类型定义`，由大到小考虑。
- 结果数据如何`指导施工`。