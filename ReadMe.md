# 图库更新

**==注意==**

- 因Github修改过用户名，老的文档可能需要修改
- 每次release不要超过**50M**
  - [使用GitHub自建免费小型图床](https://feyoudao.cn/pages/d945b5/)



## 更新分支流程

- 发布旧的分支
  - Pycharm
    - 0 可以先备份整个项目目录
    - ① pull 远程
    - ② 压缩历史提交为一个，force push
    - ③ 创建同分支名的Tag，push的时候选择 推送标记：所有
  - Github
    - ① [删除remote分支](https://github.com/FirstDiscoverer/ImageHosting/branches)
    - ② [发布Release](https://github.com/FirstDiscoverer/ImageHosting/releases/new)
- 创建新的分支
  - Pycharm
    - ① 切换到base分支 / 最底部分支
    - ② 基于base/ 最底部分支 创建分支：r/2X/0101、r/2X/0401、r/2X/0701、r/2X/1001
    - ③ 修改 PicGo中的 分支名、自定义域名中的分支



## PicGo设置

- 图床设置(Github)
  - 设定仓库名：FirstDiscoverer/ImageHosting
  - **设定分支**：master、r/24/0101
  - 设定Token：文档
  - 设定存储路径：img/      (必须有/)
  - **设定自定义域名**：
    - https://raw.githubusercontent.com/FirstDiscoverer/ImageHosting/**master**
    - https://cdn.jsdelivr.net/gh/FirstDiscoverer/ImageHosting@**master**
- PicGo设置
  - 设置代理和镜像 ✗
  - 打开更新助手 ✗
  - 开机自启 ✓
  - 上传前重命名 ✓
  - 时间戳重命名 ✓
  - 开启上传提示  ✓
  - 上传后自动复制URL  ✓
  - 请选择显示的图床：Github



