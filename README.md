# vue-pushpin
## 基于vue2.0的图钉组件
# params
## @prop position 停靠的位置 JSON 默认：{top: 0, left: 0}
## @prop scrollElement 监听滚动的元素 String 默认：document
## @prop advance 激进策略，采用position: sticky; Boolean 默认：false
## @prop onFixed isFixed=true时触发的钩子函数，此事件对advance=true时无效, 函数参数（{position: Object, clientRect: Object}） type: Function
## @prop onFixDisabled isFixed=false时触发的钩子函数，此事件对advance=true时无效, 函数参数（{position: Object, clientRect: Object}） type: Function
## @slot inner 填入图钉的内容 默认：空
