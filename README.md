# vue-message
this is message components
## 组件使用示例:
### 在main.js中注册全局组件:
```
import Message from '@/components/message'
Vue.use({
  Message
})
```
#### script代码:
```
this.$message('请先登录')
this.$message.warning('XXX')
this.$message.success('XXX')
this.$message.error('XXX')
```
>>注意这是没有直接使用Vue.use(Message) 这样会默认执行一次Message.install方法
---
