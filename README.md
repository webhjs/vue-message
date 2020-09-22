# vue-message
this is message components
## 组件使用示例:
### 1. 将项目组件克隆到components目录下:

### 2. 在main.js中注册全局组件:

```
import Message from '@/components/vue-message'
Vue.use({
  Message
})
```
>>注意这是没有直接使用Vue.use(Message) 这样会默认执行一次Message.install方法
---
#### 3. script代码就可以在项目的任意位置使用:
```
this.$message('请先登录')
this.$message.warning('XXX')
this.$message.success('XXX')
this.$message.error('XXX')
```
