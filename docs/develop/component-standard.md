# 组件开发规范

## 代码规范

### 主要原则

* 使用最新es6语法
* 通过项目的eslint

### 具体细则

* 用const或者let代替var
* 依赖包括工具函数分离成单独的js文件import

#### 组件

组件命名

尽量简单、标准。如果与原生标签一样，在前面加上x，如x-input,x-textarea,x-img
export 出来的对象命名为驼峰式，如Radio,XInput,XTextarea
假设存子组件，子组件命名在父组件后面加上-item, 如flexbox及flexbox-item, tab及tab-item
组件目录

每个组件为单独的目录，位于src/components/下，目录名全小写，入口文件为index.jsx
若项目包含子组件，入口文件同样为index.jsx，同时目录下包含与组件名同名的文件，如tab.jsx、tab-item.jsx
组件属性

必须规定type或者validator进行类型验证
不要加coerce
#### 事件

命名

统一以on前缀，如on-change。这样规范的原因：
避免与原生事件(如 change) 同名冲突重复收到DOM事件且参数错误
容易读写，与其他类型属性区分
#### 模板

不能为片断模板(不会暴露至外部使用的公用小组件除外)
class和style超过两个属性要写到computed里
#### 版本发布

修改package.json的version
添加git tag
npm publish
git push origin master
git push origin tag
登录Github修改最新release的发布信息