
### Installation (安装)

```console
npm install meansjs --save
```

### API (方法)

日常开发中所需要的方法

引入插件库
```javascript
import meansJs from 'meansjs';
```

#### ASCII排序
meAscii方法必须传递一个对象;
```javascript
const params = {
  name:'zj',
  ih:'ds'
};
const meAscii = meansJs.meAscii(params); // ihdsnamezj
```

#### 排序

> * ***arr*** 数组

