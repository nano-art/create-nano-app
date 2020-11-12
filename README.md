## 通过create-nano-app下载

```bash
# 安装create-nano-cli
npm i @nano-art/create-nano-app -g

#查看所有模版列表
create-nano-app l

#根据模版创建项目
create-nano-app i
```

 
### create-nano-app l 
通过该命令可以获取 `create-nano-app` 所有模板库<br />

```bash
 ❗️   模板列表是: 

┌────┬────────────────────┬───────────────────────────────┐
│ id │ name               │ description                   │
├────┼────────────────────┼───────────────────────────────┤
│ 0  │ react-template     │ React Nano Template           │
├────┼────────────────────┼───────────────────────────────┤
│ 1  │ react-template-pro │ React Nano Template PRO       │
├────┼────────────────────┼───────────────────────────────┤
│ 2  │ react-template-ssr │ React Nano Template SSR       │
├────┼────────────────────┼───────────────────────────────┤
│ 3  │ vue-template-v3    │ Vue Nano Template Version 3.X │
└────┴────────────────────┴───────────────────────────────┘
```

 
### create-nano-app i

 通过 `create-nano-app i` 命令可以根据上方模板库名称，创建新项目
 
### 完整示例
```bash
% create-nano-app l

 ❗️   模板列表是: 

┌────┬────────────────────┬───────────────────────────────┐
│ id │ name               │ description                   │
├────┼────────────────────┼───────────────────────────────┤
│ 0  │ react-template     │ React Nano Template           │
├────┼────────────────────┼───────────────────────────────┤
│ 1  │ react-template-pro │ React Nano Template PRO       │
├────┼────────────────────┼───────────────────────────────┤
│ 2  │ react-template-ssr │ React Nano Template SSR       │
├────┼────────────────────┼───────────────────────────────┤
│ 3  │ vue-template-v3    │ Vue Nano Template Version 3.X │
└────┴────────────────────┴───────────────────────────────┘

% create-nano-app i
模板名字: react-template-pro
项目名字: my-react-project

 ✅   初始化完成！


 ❗️   cd my-react-project && npm install


```