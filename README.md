
## 项目介绍

  项目是一个类似招聘平台的webapp，reactssr 后端使用express，mongodb完成接口开发；前端使用react全家桶及系列中间件处理数据，UI主要使用Antd-Mobile。

  项目主体功能：注册->登录-完善信息->牛人与boss列表->聊天列表->聊天->个人中心

## 使用技术栈

  ### 前端

      creact-react-app
      react16
      redux
      react-redux
      redux-thunk
      react-router4
      prop-types
      axios
      browser-cookies
      antd-mobile

  ### 后端  

      node
      express
      mongoose
      utility
      cookie-parser
      body-parser


## 项目目录

        .
        ├── README.md
        ├── config               // 开发环境的配置
        ├── public
        │   ├── index.html       // 项目页面入口文件
        ├── package.json         // 项目配置文件
        ├── scripts              // npm scrips 命令配置
        ├── server               // 后端配置
        │   ├── server.js        // 服务启动文件
        │   ├── model.js         // 数据库配置
        │   ├── userRoute.js     // 接口配置    
        ├── src
        │   ├── static           // 公用资源
        │   ├── components       // 所有组件
        │   ├── container        // 所有页面
        │   ├── redux            // redux管理
        │   ├── http.js	         // axios配置
        │   ├── index.js         // 入口文件
        │   ├── util.js          // 功能函数封装
        │   └── reducer.js       // 所有reducer合并


## 运行项目

  ### 环境依赖

      项目运行前须要安装NodeJs&MongoDB，Mongo端口为27017，express服务器端口9093，访问地址为：localhost

  ### 运行项目
      
      首先需要使用命令行工具CD到根目录，按顺序执行如下命令

      第一个窗口用于拉取依赖&启动服务器
      npm install //拉取依赖
      node server/server.js //启动服务

      第二个窗口用于启动MongoDB
      全局直接执行命令 Mongo

      第三个窗口用于启动项目
      npm run start









This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
