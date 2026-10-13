# 王炫茹的9岁生日魔法派对 · GitHub Pages 上传版

来自小姨的生日惊喜 🎀

这是可以直接部署到 GitHub Pages 的完整静态网站。图片、音乐、动画、麦克风互动、贺卡和纪念卡生成代码都已包含在一个 `index.html` 中，无需安装工具、运行构建或配置服务器。

## 最省事：只上传一个文件

1. 登录 GitHub，点击右上角 `+` → `New repository`。
2. 仓库名称可以填写 `xuanxuan-birthday`。如果使用 GitHub Free 的普通个人仓库，需要选择 `Public` 才能使用 Pages；其他支持私有仓库 Pages 的付费方案可按自己的计划选择。建议勾选添加 README，然后点击 `Create repository`。
3. 在仓库页面点击 `Add file` → `Upload files`。将本包里的 **index.html 文件本身** 拖进去，提交到 `main` 分支。如果页面让你先提出更改，再按照页面提示完成提交或合并，直到 `main` 分支能看到该文件。
4. `index.html` 应该直接出现在仓库第一层，和 README 在同一层。不要把 ZIP 压缩包直接上传，也不要只上传外层文件夹。
5. 点击仓库 `Settings` → 左侧 `Pages`。
6. 在 `Build and deployment` 下，将 `Source` 设为 `Deploy from a branch`。
7. 将 `Branch` 选为 `main`，文件夹选为 `/(root)`，点击 `Save`。
8. 等待 GitHub 完成部署，在同一个 Pages 设置页面找到网址或 `Visit site`。将这个网址发给炫炫即可。

如果你使用上述仓库名称，普通项目网页地址的形式为：

    https://你的GitHub用户名.github.io/xuanxuan-birthday/

这是地址格式示例；请以 GitHub Pages 设置页面实际给出的网址为准。

## 文件说明

- `index.html`：必须上传；它就是整个生日网站。
- `.nojekyll`：可选，供 GitHub 按静态文件方式发布。Mac 默认会隐藏此文件；不上传它也可以按上面的单文件方式部署。
- `README.md`：本说明，可选择上传。

本 ZIP 内没有额外的外层目录，解压后即可找到 `index.html`。网页文件约 6.3 MiB，低于 GitHub 网页上传的单文件 25 MiB 上限。

## 使用体验

- 点击“开启生日派对”后才开始播放音乐，符合浏览器的播放规则。
- 使用 GitHub Pages 给出的 HTTPS 地址，有助于正常申请麦克风权限。
- 麦克风只能在小朋友点击“用麦克风吹蜡烛”后开启，声音在本地检测，不录制、不上传。浏览器未开放麦克风时，直接点击按钮也能完成许愿。
- 保存生日纪念卡时，手机也可以长按生成的图片保存。
- 手机上建议使用 Safari 或 Chrome 等浏览器打开；如果聊天应用的内置浏览器限制麦克风或图片保存，可以选择“在浏览器打开”。

## 关于访问范围

GitHub Pages 普通个人部署得到的是公开网页；使用私有仓库也不等于网页需要登录。这意味着他人可能看到生日姓名、祝福及素材。如果你希望只有指定的人能访问，需要使用支持访问控制的托管方案。

本页面已添加 `noindex` 提示搜索引擎不要收录，但这不是密码保护，也不会阻止他人直接访问或转发链接。

## 官方操作说明

- 上传文件：https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
- Pages 配置：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
