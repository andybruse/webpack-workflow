# webpack-workflow
用wepack、react搭建一个自动化符合es6标准的前端工程模版

* webpack作为打包工具
* koa或者express提供假数据接口
* 使用react、es6标准编写项目代码

####项目目录文件说明
>- webapp/               # 根目录
>  - src/                # 开发目录
>    + css/              # css资源目录
>    + img/              # 图片资源目录
>    - js/               # jsx资源目录
>      - components/     # 整合组件目录
>          - foo/        # 组件foo
>            + css/      # 组件foo的样式
>            + js/       # 组件foo的逻辑
>            + tmpl/     # 组件foo的模板
>            index.js    # 组件foo的入口
>          + bar/        # 组件bar
>      + lib/            # 第三方纯js库
>      ...               # 根据项目需要任意添加的代码目录
>    index.html          # webapp入口文件index
>  - assets/             # 发布目录
>    + js/               # 编译输出的js目录
>    + img/              # 编译输出的图片目录
>    + css/              # 编译输出的css目录
>    index.html          # 编译输出的入口index
>  + mock/               # 假数据目录
<!-- >  app.js                # 本地server入口
>  routes.js             # 本地路由配置
>  webpack.config.js     # webpack配置文件
>  gulpfile.js           # gulp任务配置 -->
>  package.json          # 项目配置
>  README.md             # 项目说明
