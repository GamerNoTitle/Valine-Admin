|    变量名     |                             说明                             |                             示例                             |
| :-----------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|   SITE_NAME   |                       [必填] 网站名称                        |                           小康博客                           |
|   SITE_URL    |               [必填] 网站地址，最后不要加 `/`                | [https://blog.antmoe.com](https://web.archive.org/web/20240908071936/https://blog.antmoe.com/) |
|   SMTP_USER   |           [必填] SMTP 服务用户名，一般为邮箱地址。           | [admin@antmoe.com](https://web.archive.org/web/20240908071936/mailto:admin@antmoe.com) |
|   SMTP_PASS   | [必填] SMTP 密码，一般为授权码，而不是邮箱的登陆密码，请自行查询对应邮件服务商的获取方式 |                             123                              |
| SMTP_SERVICE  | [新版支持] 邮件服务提供商，[内置支持](https://web.archive.org/web/20240908071936/https://nodemailer.com/smtp/well-known/#supported-services) |                             163                              |
|  SENDER_NAME  |                     [必填] 寄件人名称。                      |                           小康博客                           |
|   TO_EMAIL    |         [可选] 博主通知收件地址，默认使用 SMTP_USER          | [admin@antmoe.com](https://web.archive.org/web/20240908071936/mailto:admin@antmoe.com) |
| BLOGGER_EMAIL | [可选] 如果设置则作为后台管理员邮箱（`/sign-up` 页面设置），不设置则默认以 `SMTP_USER` | [admin@antmoe.com](https://web.archive.org/web/20240908071936/mailto:admin@antmoe.com) |
| TEMPLATE_NAME |                  [必填] 设置提醒邮件的主题                   |                           custom2                            |
|  AKISMET_KEY  | [可选] Akismet Key 用于垃圾评论检测，设为 MANUAL_REVIEW 开启人工审核，留空不使用反垃圾 |                             xxxx                             |
|   ADMIN_URL   |             [可选] 后台管理地址 (**非博客地址**)             | [https://xxxx.leanapp.cn/](https://web.archive.org/web/20240908071936/https://xxxx.leanapp.cn/) |
|    COMMENT    |                   [可选] 评论 div 的 ID 名                   |                        #post-comment                         |
|     SCKEY     |                   [可选] server 酱的 SCKEY                   |                             xxx                              |
|  AKISMET_KEY  |             [可选] Akismet Key 用于垃圾评论检测              |                         xxxxxxxxxxxx                         |
|   QMSG_KEY    |                     [可选] Qmsg 酱的密钥                     |                            xxxxx                             |
|      QQ       | [可选] Qmsg 酱发送的 qq，不填为全部。支持多个，用英文逗号分隔即可 |                          535668586                           |
| DISABLE_EMAIL |                [可选]，填写则代表停止发送邮件                |                             true                             |
|   QQ_SHAKE    |                [可选]，填写代表发送 QQ 戳一戳                |                             true                             |
|      ICP      |               [可选] 备案信息，直接填写即可。                |                    京 ICP 备 19022312 号                     |
|     INFO      |            [可选] 自定义信息输出，支持 HTML 代码             |                `<p style='color:red'>test<p>`                |
|    favicon    |                   [可选] 网页 favicon 图标                   | [https://cdn.jsdelivr.net/gh/sviptzk/StaticFile_HEXO/butterfly/img/favicon.ico](https://web.archive.org/web/20240908071936/https://cdn.jsdelivr.net/gh/sviptzk/StaticFile_HEXO/butterfly/img/favicon.ico) |
|  SPAM_WORDS   |       [可选] 需要对屏蔽的关键词，关键词用半角逗号分隔        |                          单号，物流                          |
|  MAIN_COLOR   |          [可选] 仅针对 `custom2` 模板主题的主要颜色          |                           #ff9191                            |
|   MAIN_IMG    |            [可选] 仅针对 `custom2` 模板主题的头图            |              `https://bing.rthe.net/wallpaper`               |

当使用自定义邮件服务器时（需将 `SMTP_SERVICE` 变量删掉哦！）

|   变量名    |                             说明                             |       示例        |
| :---------: | :----------------------------------------------------------: | :---------------: |
|  SMTP_HOST  |  邮件服务提供商 SMTP 地址，此项需要自行查询或询问其服务商。  | `smtp.ym.163.com` |
|  SMTP_PORT  | 邮件服务提供商 SMTP 端口，*此项需要自行查询或询问其服务商*。 |        994        |
| SMTP_SECURE | 是否启用加密，默认为 `true`，一般不需要设置，如有特殊请自行配置。 *此项需要自行查询或询问其服务商*。 |       true        |

此项目的主题字段

|  主题   |                             说明                             |
| :-----: | :----------------------------------------------------------: |
| default |                           默认主题                           |
| rainbow |                        原版的 rainbow                        |
| custom1 | 基于[🎉 梨花町の肾兄さん 🎉](https://web.archive.org/web/20240908071936/https://pbas.club/)的模板 |
| custom2 |                     对 custom1 的改进版                      |