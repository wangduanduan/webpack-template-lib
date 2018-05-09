# 1. webpack-template-lib
webpack 构建第三方库模板

# 2. 使用方法

## 2.1. clone本项目
```
git clone https://github.com/wangduanduan/webpack-template-lib.git
```

## 2.2. 重命名以及删除git原始数据仓库

git clone后，会在命令执行目录下生成一个webpack-template-lib文件夹，你需要把这个文件夹名字改成你需要的名字

```
// 将webpack-template-lib改名为myLib文件夹
mv webpack-template-lib my-lib

// 进入my-lib文件夹，将原始的.git仓库删除
cd my-lib
rm -rf .git

// 如果需要添加新的git仓库，可以执行
git init
git remote add origin https://github.com/wangduanduan/some-others-name.git
```

## 2.3. 安装依赖

```
yarn // or npm i
```

## 2.4. 运行
```
yarn start // 开发环境 使用webpack.dev.js配置文件，在本地9000端口开启静态文件服务器
yarn run build // 构建代码
```

