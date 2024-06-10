clash核心已删除，导致无法正常编译clashforandroid，这是我电脑中的备份，建议将文件下载后解压至/root/ClashForAndroid/core/src/foss/golang/clash ，此处/root/ClashForAndroid改成自己项目目录
修改/core/src/main/golang/clash/go.mod 底部加上replace github.com/Dreamacro/clash => /root/ClashForAndroid/core/src/foss/golang/clash
