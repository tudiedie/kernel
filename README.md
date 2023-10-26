## GitHub Action 全自动编译内核

改自 P3TERX 的脚本。

BBRplus Action 编译的内核仅限 Cloud VMS，实体机不建议安装使用。

BBRplus from https://github.com/UJX6N

XanMod(停止维护) from https://xanmod.org/  

关联内核脚本：https://github.com/tudiedie/Linux-NetSpeed

生成补丁：diff -up config-1 config-2 >config.patch

ARM config from：

https://kojihub.stream.centos.org/koji/packageinfo?packageID=800

https://archlinuxarm.org/packages/aarch64/linux-aarch64/files/config
