# godaddy-ddns

Slightly modified version of godaddy.sh from Nazar78. Compatible with OpenWRT.

Bash required to run the script :  # opkg install bash

http://teanazar.com/2016/05/godaddy-ddns-updater/

All credits goes to Nazar78 for his great work!

AX3600 上面安装jq 比较麻烦，一直缺乏libc 依赖，也很难在openwrt的包里面找到。于是直接把jq 相关replace 掉，也能正常运行

Godday 里面创建api key， 环境需要选择Production 而不是ote， 两者是有区别的。 创建的时候把api key 和sec 保存下来。 在脚本中把key sec domain subdomain 都替换成你自己的数据
