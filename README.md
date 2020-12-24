# api-manager
api接口全局管理，restful风格

### 依赖
- vue2.x
- 安装axios，把实例赋值给Vue.prototype.$axios属性

### 安装
```javascript
import api from '?/api/plugin'

Vue.use(api);
```

### 使用
```javascript
// in Vue
this.Api.apiName.get()

// url附加参数
this.Api.apiName.put('/1', {})

// 请求加载状态
this.Api.apiName.loading.get
```
