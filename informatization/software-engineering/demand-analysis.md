# 需求分析（P35）

> 需求分析是把杂乱无章的**用户要求**转化成为**用户需求**的工作。好的需求具有无二义性、完整性、一致性、可测试性、确定性、可跟踪性、正确性、必要性等特征。

## 分析方法

主要有两种需求分析方法：**SA（结构分析）**和**OOA（面向对象分析）**。

### SA结构分析

基本思想是“分解”。采用功能分解的方法来描述系统功能，系统功能被分解到各个功能模块中，通过描述细分的功能模块达到描述整个系统功能的目的。

缺点是容易混淆需求和设计的界限，细分的功能模块实际上已经包括了部分的设计在内，而作为用户而言是不需要知道设计内容的，因此想要专注于描述系统所能提供的服务还得用OOA。

### OOA面向对象分析

如其名所示OOA表明了需求分析的方法是面向对象。OOA的结果是产生一个符合用户需求的OOA模型，OOA模型包括**用例模型**和**分析模型**。

#### 用例模型

一般会经历四个阶段，前三个阶段为必要阶段：**识别参与者、合并需求、细化用例描述**和**调整用例模型**。

用例之间的关系有**包含、扩展**和**泛化**。

#### 分析模型

描述系统的基本**逻辑结构**（如何实现功能的），展示对象和类如何组成系统（静态模型），以及它们如何保持通信，实现系统行为（动态模型）。

建立分析模型的过程大致分为**定义概念类、确定类之间的关系、为类添加职责、建立交互图等（CRC类-责任-协作者）**。

类之间的主要关系有**关联、依赖、泛化、聚合、组合和实现**等。聚合和组合的区别是聚合中的部分可以用于其他的整体，如车轮之于汽车；组合中的部分不能用于其他整体，如部门之于公司。

## SRS软件需求说明书

是需求开发活动的产物，是整个开发工作的基础。SRS是软件开发过程中最重要的文档之一，对于任何规模和性质的软件项目都必不可少。

SRS包括范围（功能列表、产品结构图）、引用文件、需求、合格性规定、需求可追踪性（需求中的需求项要有对应的测试用例）、尚未解决的问题、注解和附录。

## 需求验证

也称为需求确认，包括以下几个方面的内容。

1. SRS正确描述预期的、**满足项目干系人**需求的系统行为和特征。
2. SRS中的软件需求是从**系统需求、业务规格和其他来源**中正确推导而来的。
3. 需求是**完整的和高质量的**。
4. 需求的表示在所有地方都**一致**。
5. 需求为继续进行系统设计、实施和测试**提供**了足够的**基础**。

实际工作中一般通过**需求评审和需求测试**工作来对需求进行验证。

## UML

UML是一种定义良好、易于表达、功能强大且普遍使用的建模语言。包括**构造块**、**规则**和**公共机制**。

### 事物

有三种基本的构造块：事物、关系、图。

事物包括结构事物、行为事物、分组事物和注释事物。

### 关系

包括依赖、关联、泛化、实现。

### UML2.0中的图

类图、对象图、构件图、组合结构图、用例图、顺序图（时序图）、通信图、定时图、状态图、活动图、部署图、制品图、包图、交互概览图。

### UML视图

逻辑视图、进程视图、实现视图、部署视图、用例视图（用户沟通）。

