## 项目说明

1. 项目通过typescript来编写组件代码

2. Vue组件的定义, 需要调用@core 中的修饰函数来设定相关的属性

3. 组件的引入, 通过动态方式引入 *() => import('')*



## 项目结构说明

config: 构建环境配置文件

docs: 文档相关目录

src: 源码

  --app: 项目组件样式目录
  --lib: 核心的相关功能
  --packages: 组件目录
  --public: 公共资源目录, 主要是静态文件相关

types: 定义类型的目录