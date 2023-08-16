# ant-design-pro

原始仓库：https://github.com/ant-design/ant-design-pro

企业中后台模板。Ant Design Pro 是基于 Ant Design 和 umi 的封装的一整套企业级中后台前端/设计解决方案，致力于在设计规范和基础组件的基础上，继续向上构建，提炼出典型模板/业务组件/配套设计资源，进一步提升企业级中后台产品设计研发过程中的『用户』和『设计者』的体验。

# 使用

1. **我们提供了 pro-cli 来快速的初始化脚手架**

```node
# 使用 npm
npm i @ant-design/pro-cli -g
pro create myapp
```

2. **选择 umi 的版本**

```
? 🐂 使用 umi@4 还是 umi@3 ? (Use arrow keys)
❯ umi@4
  umi@3
```

如果选择了 umi@4 版本，暂时还不支持全量区块。

如果选择了 umi@3，还可以选择 pro 的模板，simple 是基础模板，只提供了框架运行的基本内容，complete 包含所有区块，不太适合当基础模板来进行二次开发

```
? 🚀 要全量的还是一个简单的脚手架? (Use arrow keys)
❯ simple
  complete
```

3. **安装依赖：**

```
$ cd myapp && tyarn
// 或
$ cd myapp && npm install
```

4. **bug解决**

[解决 npm install 时出现的.git can‘t be found (see https://git.io/Jc3F9)的问题 run `npm fund` for details问题解决](https://blog.csdn.net/lvoelife/article/details/126172368)

[nodejs新版本引起的：digital envelope routines::unsupported](https://blog.csdn.net/fengyuyeguirenenen/article/details/128319228)

5. **启动项目**

```
npm run start
```