
### ServerSide
https://github.com/riobard/go-shadowsocks2

1st:
go get -u -v github.com/riobard/go-shadowsocks2
2nd:
cd /go/bin 
./go-shadowsocks2 -s ss://AES-256-CFB:abcd1234@:8488 -verbose

### Tun2socks-mobile-demo

*需要配置gomobile的环境，才能进行编译*

go-tun2socks-mobile 生成的framework 使用demo
*-mobile.go 根据报错做了简单的修改，注意对应参数个数以及依赖的go-tun2socks的方法是否发生了变化

Thx:
@ BearFree的VpnManager 
@ eycorsican/go-tun2socks / go-tun2socks-mobile 
@ riobard/go-shadowsocks2
@ SimpleTunnel 


TBD:
  1.没有仔细查api,需要做route traffic可能是需要设置代理添加规则（ss）
  2.修改-mobile.go 暴露出V🤮ray可以使用的方法，有空再来弄下
