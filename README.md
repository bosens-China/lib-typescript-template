# lib-typescript-template

![mlt](https://img.shields.io/badge/License-MIT-brightgreen)

构建 Typescript 的一个模板仓库，出现它的契机是因为随着工程化的出现，构建一个项目再也不是一个`.js`文件就能解决的了。

为了避免简单的错误，引入了 Eslint 的代码规范；

为了解决 javaScript 过于灵活出现了 Typescript；

为了提高代码质量出现了 Jest 等一系列测试工具；

为了不必等待使用最新的 ECMAScript 语法，出现了 Babel；

上面的一切都在说明前端从刀耕火种迈向了现代化，但是于此同时，繁琐的配置文件太考验一个人的耐心了，重复的工作是每个程序员都要避免的，这个仓库就是将一些常用的配置文件整合起来做到拉取完成就可以使用。

## 使用方式

```sh
git clone https://github.com/bosens-China/lib-typescript-template.git
cd lib-typescript-template
yarn install
# 更新git推送地址
git remote rm origin
git remote add origin [git地址]

```

**tip**: 尽量使用 yarn 安装

> 如果拉取 Git 速度过慢，可以使用[github-clone](https://github.com/bosens-China/github-clone)拉取

## 功能列表

- Eslint 规则的 [Airbnb](https://github.com/airbnb/javascript)；与 Airbnb 风格一致的 [Prettier](https://prettier.io/) 格式化配置文件
- Git 提交规范和校验
- [jest](https://jestjs.io/) 单元测试
- [rollup](https://rollupjs.org/guide/en/) 构建工具的开箱即用
- [ts-node](https://github.com/TypeStrong/ts-node) 断点调试(只支持 Visual Studio Code)

## 其他

运行 `yarn run changelog` 生成 CHANGELOG.md 文件

运行 `yarn run comment` 进行 Git 提交

如果你有好的想法欢迎 pr

## 协议

[MIT License](/License)
