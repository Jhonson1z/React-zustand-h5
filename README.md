# react-h5-app

#### 介绍
> 使用 React+Vite 进行em-app的H5端重构，实现了对移动端的适配
> 
> 集成了zustand，使状态管理更加清晰简便
> 
> 集成了unocss，不再需要为少量的样式而创建CSS类

#### 软件架构
> vite 4.1.0
> 
> React 18.2.0
> 
> react-router-dom 6.8.1
> 
> zustand 4.3.2
> 
> antd 5.1.7
> 
> axios 1.3.2
> 
> unocss 0.49.4
> 
> ahooks 3.7.4

#### 安装教程

`git clone https://gitee.com/INeedAGodDamnGun/react-h5-app.git`

#### 使用说明

1.  `npm i` or `pnpm i` or `yarn`
2.  `npm run dev` or `pnpm dev` or `yarn run dev`

### 配置说明
本项目基于`Vite`进行构建，请求地址已作为环境变量配置于`.env.development`文件中

> 如果需要**区分不同环境下的请求地址**，按以下操作进行👇
> 
> 1. 于项目根目录（和`.env.development`文件同级）创建`.env.[*]`文件
> 2. 在新文件中配置`VITE_APP_API_BASE_URL=请求地址`
> 3. 在`package.json`文件的`scripts`对象中配置` " mode ": " vite --mode * " `
> 4. 配置完成后执行`pnpm mode`即可使用新创建的环境变量

 _PS：`vite.config.ts`文件中的`loadEnv`函数仅适用于该文件，如果需要在其他地方使用环境变量，请使用`import.meta.env.变量`的方式引用，详情见[Vite环境变量](https://cn.vitejs.dev/guide/env-and-mode.html)_ 

