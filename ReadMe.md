# 图库更新

**==注意==**

- 因Github修改过用户名，老的文档可能需要修改
- 每次release不要超过**50M**
  - [使用GitHub自建免费小型图床](https://feyoudao.cn/pages/d945b5/)



## 更新分支流程

- 发布旧的分支
  - Pycharm
    - ① pull 远程
    - ② 压缩历史提交为一个，force push
    - ③ 创建同分支名的Tag，push的时候选择 推送标记：所有
  - Github
    - ① [删除remote分支](https://github.com/FirstDiscoverer/ImageHosting/branches)
    - ② [发布Release](https://github.com/FirstDiscoverer/ImageHosting/releases/new)
- 创建新的分支
  - Pycharm
    - ① 切换到base分支
    - ② 基于base创建分支：r/2X/0101、r/2X/0401、r/2X/0701、r/2X/1001
    - ③ 修改 PicGo中的 分支名、自定义域名中的分支



## PicGo设置

- ~~代理~~
- 打开以下功能：
  - 上传前重名名
  - 时间戳重命名
  - 上传提示 
  - 自动复制URL 



