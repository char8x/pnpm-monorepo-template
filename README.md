# Pnpm Monorepo Template

> https://zhuanlan.zhihu.com/p/503994684
> https://juejin.cn/post/7055281852789047304

```sh
# 在子目录下初始化
pnpm init

# 在 root 下执行
pnpm i cowsay -D --filter demo2

# 给 demo2 安装依赖
pnpm i demo2 --filter demo1

pnpm remove axios
pnpm remove axios --filter  @monorepo/http

pnpm link --global
pnpm link --global <pkg>

pnpm why -r

```
