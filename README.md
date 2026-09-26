# 使用

```bash
adb push taiji_cpe-ota-1.260921.4_c.tar.gz /run/ota.tar.gz
adb shell "cd /tmp && tar xzf /run/ota.tar.gz install.sh && sh install.sh"
```



# 关于 GPLv3

GPLv3 是自由软件基金会 2007 年发布的强 Copyleft 开源协议：任何人都可以自由使用、研究、修改和再分发软件，但只要把（含其代码的）作品对外分发，就必须整体以 GPLv3 授权并向接收者提供完整源码，不能闭源或换更严的协议；v3 相比 v2 新增了专利自动授权与诉讼反制、消费电子设备反 Tivoization（固件必须允许用户运行自己修改的版本）等条款。



# LICENSE

MIT
