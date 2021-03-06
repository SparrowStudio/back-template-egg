<!--
 * @description: 
 * @author: bubao
 * @date: 2020-10-20 13:08:31
 * @last author: bubao
 * @last edit time: 2020-10-20 20:34:37
-->

# back-template-egg

Sparrow Studio 项目组后端项目开发模板，方便快速创建新项目。

## QuickStart

<!-- add docs here for user -->
使用 vscode 开发，需要安装一下插件

- [eggjs](https://github.com/eggjs/vscode-eggjs): eggjs 开发提示插件。
- [egg-jump-definition](https://marketplace.visualstudio.com/items?itemName=egg-jump-definition.egg-jump-definition): egg 文件跳转。
- [eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): eslint 插件

该项目使用 yarn 代替 npm。

获取项目代码

```sh
git clone https://gitee.com/sparrow-studio/back-template-egg.git
```

查看远程地址

```sh
git remote get-url origin
```

删除原来的远程地址

```sh
git remote remove origin
```

添加新的远程地址

```sh
git remote add origin <新项目的地址>
```

推送远程仓库

```sh
git push -u origin master
```

see [egg docs][egg] for more detail.

### Development

```bash
$ yarn
$ yarn run dev
$ open http://localhost:7001/
```

### Deploy

```bash
$ yarn start
$ yarn stop
```

### yarn scripts

- Use `yarn run lint` to check code style.
- Use `yarn test` to run unit test.
- Use `yarn run autod` to auto detect dependencies upgrade, see [autod](https://www.npmjs.com/package/autod) for more detail.

[egg]: https://eggjs.org

## 代码推送

因为该模板为了更好的团队协作，使用`husky`和`commitizen`规范了代码的提交，并使用`eslint`检查并修复代码格式。所以在提交时，使用`commitizen`的命令`yarn run cz`代替`git commit`来提交代码。
