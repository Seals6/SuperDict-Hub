# 网络安全设备默认用户密码

```bash
天融信防火墙，不需要证书 登录地址:https://192.168.1.254 用户名:superman 密码:talent 技术支持热线：8008105119
天融信防火墙，不需要证书 登录地址:https://192.168.1.254：8080 用户名:superman 密码:talent！23 遇到设备需要把旧设备配置备份下来，再倒入新设备基于console口登陆，用户名，密码跟web界面一致 system config reset 清除配置 save 保存 联想网御防火墙，需要证书（最好用IE浏览器登录）
登录地址:https://10.1.5.254:8889 用户名:admin 密码:leadsec@7766、administrator、bane@7766 技术支持热线：4008107766 010-56632666
深信服防火墙（注安全设备管理地址不是唯一的） https://10.251.251.251
https://10.254.254.254 用户名：admin 密码：admin 技术支持热线：4006306430
启明星辰 https://10.1.5.254:8889 用户名：admin 密码：bane@7766
https://10.50.10.45:8889 用户名：admin 密码：admin@123 电脑端IP：10.50.10.44/255.255.255.0 技术支持热线：4006243900
juniper 登录地址:https://192.168.1.1 用户名:netscreen 密码:netscreen
Cisco 登录地址:https://192.168.0.1 用户名:admin 密码:cisco
Huawei 登录地址:http://192.168.0.1 用户名:admin 密码:Admin@123
H3C 登录地址:http://192.168.0.1 用户名:admin 密码:admin 技术支持热线：4006306430
绿盟IPS https://192.168.1.101 用户名: weboper 密码: weboper 配置重启生效
网神防火墙GE1口 https://10.50.10.45 用户名：admin 密码：firewall 技术支持热线：4006108220
深信服VPN： 51111端口 delanrecover
华为VPN：账号：root 密码：mduadmin
华为防火墙： admin Admin@123 eudemon
eudemon Juniper防火墙： netscreen netscreen
迪普 192.168.0.1 默认的用户名和密码（admin/admin_default)
山石 192.168.1.1 默认的管理账号为hillstone，密码为hillstone
安恒的明御防火墙 admin/adminadmin
某堡垒机 shterm/shterm
天融信的vpn test/123456
```

```bash
绿盟安全产品默认密码排查列表

IPS入侵防御系统、SAS­H运维安全管理系统、SAS安全审计系统、DAS数据库审计系统、RSAS远程安全评估系统、WAF WEB应用防护系统
sysauditor/sysauditor
sysmanager/sysmanager
supervisor/supervisor
maintainer/maintainer
webpolicy/webpolicy
sysadmin/sysadmin
conadmin/conadmin
supervis/supervis
webaudit/webaudit
sysadmin/sysadmin
conadmin/nsfocus
weboper/weboper
auditor/auditor
weboper/weboper
nsadmin/nsadmin
admin/nsfocus
admin/admin
shell/shell
```

华为网络安全产品默认用户密码

|                        产品系列/名称                         | 版本号      | BootROM（密码）                             | Console（用户名/密码）              | Telnet（用户名/密码）              | Web（用户名/密码）                                           | 备注                                                         |
| :----------------------------------------------------------: | ----------- | ------------------------------------------- | ----------------------------------- | ---------------------------------- | ------------------------------------------------------------ | :----------------------------------------------------------- |
|                         AntiDDoS1500                         | V100R001    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | Web用户指的是登录ATIC管理中心的用户。                        |
|                         AntiDDoS8000                         | V100R001    | WWW@HUAWEI                                  | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | Web用户指的是登录ATIC管理中心的用户。                        |
|                           ASG2000                            | V100R001    | O&m15213                                    | admin/Admin@123                     | 不支持Telnet管理。                 | admin/Admin@123                                              | Web用户包括登录ASG设备Web界面的用户和登录ASG管理中心的用户。 |
|                      AVE2200/2600/2800                       | V100R001    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                           AVE2900                            | V300R001    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                      Eudemon 100E/200S                       | V200R001C03 | 8060                                        | eudemon/eudemon     admin/Admin@123 | NA                                 | NA                                                           | 无                                                           |
|                         Eudemon  200                         | V200R007C03 | 8060                                        | eudemon/eudemon     admin/Admin@123 | NA                                 | NA                                                           | 无                                                           |
|                     Eudemon 300/500/1000                     | V200R006C02 | 8060                                        | eudemon/eudemon     admin/Admin@123 | NA                                 | NA                                                           | 无                                                           |
|                        Eudemon  8000                         | NA          | 8011                                        | NA                                  | NA                                 | NA                                                           | 无                                                           |
|                      Eudemon 8040/8080                       | V300R001    | 8060                                        | eudemon/eudemon     admin/Admin@123 | NA                                 | NA                                                           | 无                                                           |
|                     Eudemon  8080E/8160E                     | V100R001C01 | 8090     www@huawei     O&m15213            | NA                                  | NA                                 | NA                                                           | 无                                                           |
|                        Eudemon1000E-N                        | V100R001    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | admin/Admin@123（系统管理员）     audit-admin/Admin@123（审计管理员） | 无                                                           |
|                        Eudemon1000E-U                        | V100R002    | usg5000     O&m15213                        | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | 没有缺省Web用户，需要手动创建。                              | 无                                                           |
|                        Eudemon1000E-U                        | V100R003    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | admin/Admin@123                                              | 无                                                           |
|                        Eudemon1000E-U                        | V200R001    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | admin/Admin@123                                              | 无                                                           |
|                        Eudemon1000E-X                        | V200R001    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | admin/Admin@123                                              | 无                                                           |
|                        Eudemon1000E-X                        | V300R001    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                     Eudemon200E-B/C/F/X                      | V300R001    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                        Eudemon200E-N                         | V100R001    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | admin/Admin@123（系统管理员）     audit-admin/Admin@123（审计管理员） | 无                                                           |
|                        Eudemon8000E-X                        | V200R001    | WWW@HUAWEI                                  | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                        Eudemon8000E-X                        | V300R001    | WWW@HUAWEI                                  | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                          IPS Module                          | V100R001    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | [admin/Admin@123](mailto:admin/Admin@123)                    | 无                                                           |
|                         NGFW  Module                         | V100R001    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | admin/Admin@123（系统管理员）     audit-admin/Admin@123（审计管理员） | 无                                                           |
|                         NIP200/1000                          | V100R001    | NA                                          | admin/admin                         | NA                                 | administrator/huawei123                                      | Web用户指的是登录管理软件控制台的用户。                      |
|                         NIP2000/5000                         | V100R001    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                         NIP2000/5000                         | V100R002    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                      SRG1200/2200/3200                       | V100R002    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                           SVN2200                            | V200R001    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                           SVN3000                            | V100R002    | svn3000     huawei_svn3000     O&m15213     | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | NA                                                           | 无                                                           |
|                           SVN5500                            | V200R001    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                           SVN5600                            | V200R003    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | [admin/Admin@123](mailto:admin/Admin@123)                    | 无                                                           |
|                           SVN5800                            | V200R003    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | [admin/Admin@123](mailto:admin/Admin@123)                    | 无                                                           |
|                           USG2100                            | V100R001    | O&m15213                                    | admin/Admin@123                     | NA                                 | [admin/Admin@123](mailto:admin/Admin@123)                    | 无                                                           |
|                           USG2100                            | V100R002    | O&m15213                                    | admin/Admin@123                     | NA                                 | [admin/Admin@123](mailto:admin/Admin@123)                    | 无                                                           |
|                           USG2100                            | V100R003    | O&m15213                                    | admin/Admin@123                     | NA                                 | [admin/Admin@123](mailto:admin/Admin@123)                    | 无                                                           |
|                           USG2100                            | V100R005    | O&m15213                                    | admin/Admin@123                     | NA                                 | [admin/Admin@123](mailto:admin/Admin@123)                    | 无                                                           |
|                           USG2100                            | V300R001    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                           USG2110                            | V100R001    | usg50     secoway     O&m15213              | admin/Admin@123                     | NA                                 | NA                                                           | 无                                                           |
|                          USG2110-X                           | V100R003C03 | O&m15213                                    | admin/Admin@123                     | NA                                 | [admin/Admin@123](mailto:admin/Admin@123)                    | 无                                                           |
|                          USG2110-X                           | V300R001    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                           USG2200                            | V100R001    | _Security                                   | NA                                  | NA                                 | NA                                                           | 无                                                           |
|                           USG2200                            | V100R002    | O&m15213                                    | NA                                  | NA                                 | NA                                                           | 无                                                           |
|                           USG2200                            | V100R003    | O&m15213                                    | admin/Admin@123                     | NA                                 | [admin/Admin@123](mailto:admin/Admin@123)                    | 无                                                           |
|                           USG2200                            | V100R005    | O&m15213                                    | admin/Admin@123                     | NA                                 | [admin/Admin@123](mailto:admin/Admin@123)                    | 无                                                           |
|                           USG2200                            | V300R001    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                           USG3000                            | V100R001    | usg3000     e200e     _Security     secoway | usg3000/usg3000     admin/Admin@123 | NA                                 | NA                                                           | 无                                                           |
|                           USG3000                            | V100R002    | usg3000     secoway                         | usg3000/usg3000     admin/Admin@123 | NA                                 | NA                                                           | 无                                                           |
|                            USG50                             | V100R001    | usg50     secoway     O&m15213              | usg50/usg50     admin/Admin@123     | NA                                 | NA                                                           | 无                                                           |
|                           USG5100                            | V100R003    | O&m15213                                    | admin/Admin@123                     | NA                                 | [admin/Admin@123](mailto:admin/Admin@123)                    | 无                                                           |
|                           USG5100                            | V100R005    | O&m15213                                    | admin/Admin@123                     | NA                                 | [admin/Admin@123](mailto:admin/Admin@123)                    | 无                                                           |
|                           USG5100                            | V300R001    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                           USG5300                            | V100R002    | usg5000     O&m15213                        | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | 没有缺省Web用户，需要手动创建。                              | 无                                                           |
|                           USG5300                            | V100R003    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | admin/Admin@123                                              | 无                                                           |
|                           USG5300                            | V200R001    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | admin/Admin@123                                              | 无                                                           |
|                        USG5300ADD&ADI                        | V100R001    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | admin/Admin@123                                              | 无                                                           |
|                           USG5500                            | V200R001    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | admin/Admin@123                                              | 无                                                           |
|                           USG5500                            | V200R002    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | admin/Admin@123                                              | 无                                                           |
|                           USG5500                            | V300R001    | O&m15213                                    | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                      USG6300/6500/6600                       | V100R001    | O&m15213                                    | admin/Admin@123                     | 没有缺省Telnet用户，需要手动创建。 | admin/Admin@123（系统管理员）     audit-admin/Admin@123（审计管理员） | 无                                                           |
|                           USG9100                            | V100R001    | O&m15213                                    | admin/Admin@123                     | NA                                 | 没有缺省Web用户，需要手动创建。                              | 无                                                           |
|                           USG9300                            | V100R001    | 8090     O&m15213                           | eudemon/eudemon     admin/Admin@123 | NA                                 | 不支持Web管理。                                              | 无                                                           |
|                           USG9300                            | V100R002    | O&m15213                                    | admin/Admin@123                     | NA                                 | 不支持Web管理。                                              | 无                                                           |
|                           USG9300                            | V100R003    | O&m15213                                    | admin/Admin@123                     | NA                                 | 没有缺省Web用户，需要手动创建。                              | 无                                                           |
|                           USG9500                            | V200R001    | WWW@HUAWEI                                  | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                           USG9500                            | V300R001    | WWW@HUAWEI                                  | admin/Admin@123                     | admin/Admin@123                    | admin/Admin@123                                              | 无                                                           |
|                         WAF2000/5000                         | V100R001    | NA                                          | admin/Admin@123                     | NA                                 | admin/Admin@123                                              | 无                                                           |
|                                                              |             |                                             |                                     |                                    |                                                              |                                                              |
| 备注：     1、各产品、版本的BootROM密码在《升级指导书》中有详细说明。      2、老产品、老版本的密码比较多样化，后来的产品、版本BootRom密码都统一为O&m15213，系统登录（包括Console、Telnet、HTTP等）用户名/密码统一为admin/Admin@123。 |             |                                             |                                     |                                    |                                                              |                                                              |