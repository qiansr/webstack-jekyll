# ➡️ [w.0hanxi.info](https://w.hanxi.infon/) - 个人书签网址导航

# 项目启动
```
  bundle install
  bundle exec jekyll serve
# => 打开浏览器 http://localhost:4000

```

# faviconserver
项目内依赖一个faviconserver服务 ，这是一个获取网站ico的go服务
https://github.com/mat/besticon

# mac下go环境安装
网盘下载地址 https://pan.baidu.com/s/1lu4Y_LB_vplz-RaAu1iv3Q
￼
下载.pkg后安装
默认安装路径一般是 /usr/local/go

vi .bash_profile   增加
export GOPATH=/usr/local/go
export GOBIN=$GOPATH/bin
export PATH=$PATH:$GOBIN

source .bash_profile 
查看Go环境变量 go env  查看版本信息 go version 

切换镜像源
七牛源：
go env -w GO111MODULE=on
go env -w GOPROXY=https://goproxy.cn,direct
阿里源：
go env -w GO111MODULE=on
go env -w GOPROXY=https://mirrors.aliyun.com/goproxy/,direct

#
