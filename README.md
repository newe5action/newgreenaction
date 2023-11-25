
## 原理

使用 GitHub Actions 的定时任务功能，每隔一段时间自动执行 `git commit`，提交信息为 "a commit a day keeps your girlfriend away"，灵感来自知乎问题[在 GitHub 上保持 365 天全绿是怎样一种体验？](https://www.zhihu.com/question/34043434/answer/57826281)下某匿名用户的回答：

> 曾经保持了 200 多天全绿，但是冷落了女朋友，一直绿到现在。

有关 Github Action 的原理，可查看官方文档 [Github Action 简介](https://docs.github.com/cn/actions/learn-github-actions/introduction-to-github-actions)

## 使用

- 修改 [ci.yml 文件的第 19、20 行](https://github.com/justjavac/auto-green/blob/master/.github/workflows/ci.yml#L19-L20) 为自己的 GitHub 账号和昵称
- (可选) 你可以通过修改 [ci.yml 文件的第 8 行](https://github.com/justjavac/auto-green/blob/master/.github/workflows/ci.yml#L8)来调整频率
