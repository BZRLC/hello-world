# hello-world
Learn Git

## 当启用两步验证后

通过https的方式连接github需要产生一个token，在`settings -> personal access tokens`

```bash
$ git config --global credential.helper.store
$ git push
Fatal: TaskCanceledException encountered.
Username for 'https://github.com': BruceZhaoR
password...
```

这里的password输入的是第一步产生的token，一串字符，复制粘贴即可。关于这个token一定要复制备份，因为你刷新了网页就会别隐藏掉，自己也看不到了。当验证成功后就可以删掉了。


参考自这个链接： <https://segmentfault.com/q/1010000000590947>