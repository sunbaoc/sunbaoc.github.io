---
title: Hello World
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)


### 配置Github (sunbaoc add )
改_config.yml文件

``` bash
deploy:

     type: git

     repo: https://github.com/sunbaoc/sunbaoc.github.io.git

     branch: master
```

然后执行命令：

``` bash
npm install hexo-deployer-git --save
```

然后，执行配置命令：
``` bash
hexo deploy
```

每次部署的步骤，可按以下三步来进行

``` bash
    hexo clean

    hexo generate

    hexo deploy
```