# 用vue3和ts开发浏览器扩展


# 1.搭建vue3+ts+vite框架


yarn dev

# 额外补充
- dependencies【生产环境】与devDependencies【开发环境】
https://docs.npmjs.com/cli/v7/configuring-npm/package-json#dependencies



比如 打包工具 webpack/eslint/babel/webpack-dev-server /vite/chalk/fs-extra/html-webpack-plugin    -- 开发环境devDependencies

npm install xxx –save-dev(-D) 表示本地安装，会被加至devDependencies部分


比如插件库 jquery/vue/react/axios---- 生产环境【dependencies】
npm install xxx –save(-S)



npm install xxx -g 表示全局安装，通常用于安装脚手架等工具