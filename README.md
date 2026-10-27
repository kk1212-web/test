# test

第一个 Git 仓库，用来跑通 clone / commit / push 的完整流程。

## 常用命令

```bash
git clone git@github.com:kk1212-web/test.git   # 克隆到本地
git status                                      # 看哪些文件改了
git add -A                                      # 把所有改动加入暂存区
git commit -m "说明改了啥"                        # 拍快照
git push                                        # 推到 GitHub
git pull                                        # 拉取别人的改动
git log --oneline                               # 看提交历史
```

## 备注

- 本机已配置 SSH 密钥，push 不需要输密码
- commit 使用的是 GitHub 的 noreply 邮箱，不会暴露真实邮箱
