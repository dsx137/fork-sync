# fork-sync

一个简单的Vercel应用  
使用webhook调用Vercel Function，将fork仓库和上游同步

```txt
POST https://xxx.vercel.app/api/sync?upstream_repo=xxx&upstream_branch=xxx&fork_repo=xxx&fork_branch=xxx&pat=xxx
```
