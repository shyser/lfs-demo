# lfs-demo

## 安装lfs
- [下载安装包](https://github.com/git-lfs/git-lfs/releases)
- 启用安装 `git lfs install`
- 添加git lfs追踪文件 `git lfs track "*.glb"`
- 按常规流程提交文件 `git add *.glb`、`git commit -m "up"`
- 查看被lfs追踪的文件列表 `git lfs ls-files`
- 按常规流程推送文件 `git push -u origin main`