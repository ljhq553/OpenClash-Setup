本文件夹存放：OpenClash的Yaml配置文件，分早期和近期使用的Yaml配置文件；
支持多机场：Yaml配置文件中允许导入多个机场订阅，仍然可独立排除无效节点，例如：剩余|重置|到期 等三个无用节点；
Yaml配置文件未提供OpenClash的全局参数、运行模式、代理端口、DNS等设置，这些均可在OpenClash的Luci界面通过菜单项进行设置，最终会生成openclash文件，保存在路由器闪存 /etc/config/下。
Yaml配置文件可用于OpenClsh，ClashMeta，ClashMi和Clash Verge等客户端。
文件名为 XXdl-OpenClash-Yaml_v0.01.yaml 的文件增加dns自定义部分，在Luci菜单 覆写设置 -> DNS设置 部分可以不做 nameserver、nameserver-policy和 proxy-server-nameserver 覆写设置。
