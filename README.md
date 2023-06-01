## 项目初始化

yarn create react-app express_dlivery --template typescript

...

## craco

安装
yarn add @craco/craco
配置
在根目录下新增 craco.config.ts
修改脚本

## 环境配置

```bash
"scripts": {
 -  "start": craco start",
 +  "start": "craco-env NODE_ENV_ENV=development craco start",
 -  "build": "react-scripts build",
 +	"build": "craco build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
  },
```
