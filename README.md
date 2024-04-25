Reality脚本安装：
wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/mack-a/v2ray-agent/master/install.sh" && chmod 700 /root/install.sh && /root/install.sh
3.可指向的网站举例
itunes.apple.com／swdist.apple.com／swcdn.apple.com／updates.cdn-apple.com／mensura.cdn-apple.com／osxapps.itunes.apple.com／aod.itunes.apple.com／download-installer.cdn.mozilla.net／addons.mozilla.org／s0.awsstatic.com／d1.awsstatic.com／images-na.ssl-images-amazon.com／m.media-amazon.com／player.live-video.net／one-piece.com／lol.secure.dyn.riotcdn.net

4.Reality指向网站筛选脚本
回落网址自动筛选脚本下载

4.1在安装目录运行cmd
4.1运行以下命令：

.\RealiTLScanner-windows-64.exe -addr 1.1.1.1 -port 443 -thread 100 -timeOut 5

（记着1.1.1.1更替为你的vps的IP再运行）
4.3根据需要随时按Ctrl+C键退出扫描
