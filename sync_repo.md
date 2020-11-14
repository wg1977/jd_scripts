> 配置具体可见：[merge-branch.yml](https://github.com/wangworld/jd_scripts/blob/main/.github/workflows/merge-branch.yml)

- 同步时间：8-23点每3个小时去同步主库
- 同步方法：action拉取主库到master分支，然后master分支再合并到main分支

PS：在main分支你可以添加自己的文件，但最好不要修改主库的代码，以免同步（合并）代码失败
