---
title: MultiItem
categories: ['java', 'recyclerview', 'android']
---
## [MultiItem](https://github.com/free46000/MultiItem)

### 一个优雅的实现多类型的RecyclerView类库 支持DataBinding Form表单录入 跨多个RecyclerView拖动

`RecyclerView`是一个大家常用的列表控件，在列表中不免会出现多种类型的布局，这时`adapter`中多种类型的判断就会充满着`switch`的坏味道，可怕的是需求变更，增加或修改新的类型时，所有的改动都在`adapter`中进行，没有一个良好的扩展性。
`MutliItem`主要就是解决这些问题，提供了多类型和`ViewHolder`创建绑定的管理器，自动进行`item type`的计算，这样`Adapter`通过依赖倒置与列表中的多类型解耦，还提高了扩展性。有以下特点：
- 直接使用业务中的实体类为`RecyclerView Adapter`设置数据源，不需要做任何封装
- `RecyclerView Adapter`零编码，解放了复杂的`Adapter`类
- 支持`DataBinding`，让你清爽的编写列表代码
- 支持Form表单录入，懒加载易复用，支持`DataBinding`、隐藏域、输入内容验证及是否变化
- 支持`Header` `Footer` 和 下拉刷新 加载更多
- 支持`Item`滑动动画
- 支持空白、错误等状态页的展示
