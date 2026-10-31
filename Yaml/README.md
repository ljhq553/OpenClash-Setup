本文件夹存放：Mihomo 内核的 Yaml 配置文件，分早期和近期使用的 Yaml 配置文件；
支持多机场：Yaml 配置文件中允许导入多个机场订阅，仍然可独立排除无效节点，例如：剩余|距离|套餐 等三个无用节点；
Yaml配置文件未提供 OpenClash 的全局参数、运行模式、代理端口等设置，这些均可在 OpenClash 的 Luci 界面通过菜单项进行设置，最终会生成 openclash 文件，保存在路由器闪存 /etc/config/下；
Yaml配置文件可用于 OpenClsh，ClashMeta，ClashMi和Clash Verge等Mihomo 内核的客户端；
文件名为 XXdl-Mihomo-Geo_v0.02.yaml 文件增加 dns 自定义部分，在Luci菜单 覆写设置 -> DNS设置 菜单项下 nameserver、nameserver-policy和 proxy-server-nameserver 等可以不设置；
文件名为 XXdl-Mihomo-Geo_v0.02.yaml 文件增加 Geo 数据库文件远程下载和自动更新，但在OpenWrt中OpenClash插件可删除这部分（因为通过Luci界面菜单项已进行了设置），手机端如Clash Meta则需要；
文件名为 XX-Mihomo-Geo-ad-icon-v0.03.yaml 文件调整规则顺序、增加广告拦截和节点组图标等。
