![](https://files.mdnice.com/user/164/42f70c6b-f984-4787-ae4c-cc86041900b6.png)

## 前言

Jan 微信插件 1.5.9-6 版本功能之多，深受广大用户喜欢，但是由于开发者丢失源码，不得不重头再来，1.5.9-6 版本已无法再更新，所以有了新的 WeChat 1.0 版本，具体功能如下图以及下文所述。

注：由于插件名称为 WeChat 容易混淆，个人为了区别且功能属于微信增强，个人命名为 WeChat Plus，与开发者无关。

## 说明
Filza 官方源地址：**https://tigisoftware.com/cydia/**

安装 **Filza File Manager 64-bit**

打开主屏幕 Filza 图标，点击任务栏 「⭐」️再点击 「App 管理器」，找到微信并点击，进入 /Library/Preferences/ 文件夹。

授权版新建 VoiceBao 文件夹、免费版新建 Voice 文件夹。

授权版把分类好的语音包放入 VoiceBao 内即可，免费版把语音包文件 ZiDingYi.plist 放入 Voice 内即可。

完成后上滑退出微信，再次打开即可。

## 更新记录

1.0.9-9 更新
1. 修复已知问题；
2. 修复删除会话；
3. 加强检查好友准确度；
4. 新增多开后台信息推送（此功能仅建议多开版本开启此功能）。

1.0.9-8 更新
1. 适配 8.0.15；
2. 修复长按文字修改带小尾巴的问题；
3. 新增对应关键字回复，一对一回复；
4. 新增群友退群提示；
5. 新增好友检测。

> 说明：检测好友前，先点击“添加标签”，并重启微信。检测结果同步到标签中，标签分类为“删除我的”、“拉黑我的”、“未知状态”、“限制登录”四种类型。限制登录为好友被封号，未知状态为检测失败。检测准确率有待提高，“删除我的”以及“拉黑我的”建议发送信息二次确认后再进行删除。
>

1.0.9-7 更新日志
1. 修复已知 Bug；
2. 新增群折叠置顶；
3. 新增滑动折叠群；
4. 新增长按文字修改。

1.0.9-61 更新日志
1. 修复点歌 Bug。

1.0.9-6 更新日志
1. 增加关键词回复语音、图片；
2. 增加关键词回复文本开关；
3. 增加收款延迟回复；
4. 增加关键词通过好友；
5. 修复试听过长语音时无法关闭播放（关闭语音包列表界面自动停止）；
7. 移除常驻后台；
8. 移除自动接听语音、视频；

1.0.9-5 更新日志
1. 优化试听，无需设置试听，可直接试听；
2. 自动回复语音 自动回复图片 ；
3. 修复关键词踢人与关键词进群冲突；
4. 修复关键词踢人导致点击群右上角「...」闪退。

1.0.9-4 更新日志
1. 移除公众号限制；
2. 增加一键地区性别清空；
3. 修复微信后台崩溃。

1.0.8-2 更新日志
1. 文字转语音新增九位人物，使用命令「#选择」选择人物（铁子哥、吆姐、青青、阿思、罗莎、小玫、柜姐、小微、小仙）；
2. 修复点歌来源，移除 QQ 音乐；
3. 修复群转账播报；
4. 修复未授权用户添加语音。

1.0.6-3 更新日志

1. 修复点击右上角 + 菜单中无水印视频闪退问题；
2. 修复点歌显示空白问题；
3. 修复长按语音不显示添加按钮问题；
4. 增加点歌资源（网易、QQ、酷狗、酷我），需前往设置中选择）；
5. 增加点歌直转语音（仅支持自己发送点歌）；
6. 删除不显示聊天对话名称。

1.0.6-2 更新日志

1. 修复短视频转语音失效问题；
2. 修复无水印解析无效问题；
3. 修复表情与图片无法加载问题；
4. 修复修改转账闪退，修改后还原问题；
5. 语音功能新增短视频转语音朋友圈（解析后可选择转语音或发朋友圈）；
6. 杂项功能新增后台模糊；
7. 语音功能新增语音包随机秒数；
8. 修改语音包文件路径（尝试解决文件莫名其妙消失问题）；

**授权版路径**

  - 微信数据/Library/Caches/VoiceBao/
  - 改为：微信数据/Library/Preferences/VoiceBao/

**免费版路径**
  - 微信数据/Library/Caches/Voice/
  - 改为：微信数据/Library/Preferences/Voice/

9. 语音包图标路径与语音包同路径；

   - Voice_Dark.png//深色模式图标
   - Voice.png//正常模式图标

1.0.6 更新日志

1. 删除屏蔽炸弹特效；
2. 修复群内转账给指定群友触发自动收款及收款后自动回复；
3. 修复表情、新建群头像、公众号文章题图等无法加载问题；
4. 修复自动回复，被拉黑后无限循环问题；
5. 修复标签无法加载问题；
6. 修复 iOS 13 以下系统版本点击语音包闪退问题；
7. 消息功能新增标签群发（设置-通用-辅助功能-群发助手，新建群发，点击顶部微信图标，选择标签群发）；
8. 朋友圈功能新增集赞，设置点赞数量，发表朋友圈后需自行点赞触发；
9. 自动功能新增转账金额修改（聊天界面长按转账信息“改金额”）；
10. 优化点歌功能；

1.0.5 更新日志

1. 新增屏蔽群代办；
2. 新增屏蔽炸弹特效；
3. 新增隐藏聊天窗口名称；
4. 修复欢迎进群发送两条的问题；
5. 修复一键删除所有会话导致微信闪退问题；
6. 修复朋友圈自动评论无法修改问题。

1.0.4 更新日志

1. 消息功能增加未接视频自动回复，未接语音自动回复；
2. 新增菜单功能，微信主界面右上角 `+` 号可选增加清理未读消息、一键删除所有会话、解析短视频（无水印下载短视频）；
3. 自动功能增加抢红包功能；
4. 朋友圈功能增加朋友圈评论通知、朋友圈评论回复、朋友圈自动点赞、常驻后台；
5. 新增 `#选择` 命令，恢复人物语音；
6. 新增聊天界面语音增加到语音包；
7. 恢复短视频链接转语音，部分短视频链接无法转语音，暂时无解；
8. 新增文字 +1、语音 +1、表情 +1 菜单图标，文字转语音菜单图标，视频转语音、转发朋友圈菜单图标，语音试听、添加至语音包菜单图标；
9. 语音包图标自定义路径及文件名称：`微信文档目录/Library/Caches/VoiceBao/Voice.png` ，深色模式图标名称为 `Voice_Dark.png`，自定义语音包图标需放两个文件。

1.0.3 更新记录

1. 兼容 libhooker 基板；
2. 修复朋友圈转发闪退问题；
3. 修复聊天界面长按文件、图片、语音闪退问题；
4. 修复点歌功能，乱触发问题；
5. 修复点击猜拳骰子会出现微信卡死或闪退问题；
6. 修复发送语音包内语言，未回到聊天界面问题；
7. 修复进群欢迎，无法选择加入的群问题；
8. 删除 1-15 号人物，文字转语音之前请再次设置；
9. 恢复语音试听功能；
10. 语调、语速设置功能取消；
11. 新增自动功能，具体功能详见思维导图或下文叙述。

> 如果你发现什么问题，也可以添加我的微信进行反馈，我将整理后反馈给开发者，毕竟我能遇到的问题有限，感谢。

## 杂项功能

- 检测好友
- 添加标签
- 自定义步数
  - 运动步数设置
  - 最低随机步数设置
  - 最高随机步数设置
- 多开保持推送
- 自定义零钱
  - 娱乐功能
- 支付加锁
- 收藏加锁
- 朋友圈加锁
  - 开启加锁功能的前提是开启锁屏功能。
- 上传长头像
- CallKit
  - 像接电话那样接听微信语音
- 显示微信号
  - 显示群友微信号，即使没有添加好友。
- 性别地区空白
- 自动确认登录
  - PC 端或者 iPad 登录微信，手机端自动确认。
- 自动勾选同步信息
- 显示并勾选登录该设备
- 好友快速备注
  - 在对话框中发送：#备注+空格+备注名，即可完成备注。
- 猜拳骰子作弊
  - 娱乐功能
- iPad 登录
  - 模拟 iPad 登录，开启后将导致朋友圈无法选择视频，订阅号文章排版改变
- 禁止下拉小程序
- 禁止下拉视频动态
- 屏蔽自己输入状态
  - 对方无法看到你的输入状态，保留对方的输入状态
- 屏蔽群代办
- 屏蔽聊天名称
  - 不显示对方名称以及群名称
- 后台模糊

## 消息功能

- 消息防撤回
- 保留聊天记录
- 自定义小尾巴
  - 小尾巴来源设置
  - 小尾巴内容设置
- 关键字回复
  - 对应回复内容设置
  - 模糊匹配
  - 关键字设置
  - 回复内容设置
- 自动回复
  - 回复内容设置
- 自动回复语言
- 自动回复图片
- 未接视频自动回复
  - 回复内容设置
- 未接语音自动回复
  - 回复内容设置
- 标签群发

## 群功能

- 伪装群主
- 伪装群管理
- 群公告
  - 批量发布创建的群聊公告
- 群解散
  - 批量解散创建的群
- 群退出
  - 批量退出加入的群
- 群踢人
  - 仅适用群主及群管理：@群友+空格+踢
- 群折叠置顶
- 滑动折叠群
- 退群提醒
- 关键字进群
- 关键字踢人
  - 设置群
- 进群欢迎
  - 指定群欢迎
  - 欢迎内容设置
- @所有人
  - 非公告形式，非群主、管理员@所有人形式，是真的@所有人
- 屏蔽@我

## 菜单功能

- 清理未读消息
- 一键删除所有会话
- 解析短视频

## 自动功能

- 红包详情
  - 点开红包后在左侧显示详情
- 自动抢红包
- 抢自己红包
- 抢个人红包
- 防止同时抢多个红包
- 抢到红包自动回复
   - 回复内容设置
   - 不回复自己红包
   - 延迟回复
- 延迟抢红包
- 不抢指定群红包
- 不抢关键字红包
- 后台推送已抢金额通知
- 抢到红包语音播报
- 红包统计
- 自动接收转账
   - 延迟接受转账
   - 接收转账语音播报
   - 收款后自动回复
      - 延迟收款回复
      - 回复内容设置
- 转账金额修改（自我安慰）
- 自动通过好友
- 关键词通过好友
   - 关键词设置
- 通过好友自动回复
  - 回复内容设置

## 朋友圈功能

- 朋友圈转发
  - **可发长视频，收费功能**；
  - 安卓设备可以查看完整视频，苹果未越狱设备只能查看 30 秒；
- 屏蔽原作者
- 隐藏朋友圈可见图标
- 朋友圈原图
  - 朋友圈发图默认选择原图
- 查看已删除评论
- 小视频进度条
  - 播放小视频显示进度条
- 小视频30秒
- 观看完整视频
- 朋友圈广告
  - 屏蔽朋友圈广告
- 朋友圈评论通知
- 朋友圈评论回复
- 朋友圈自动点赞
- 集赞

> 发送长视频，需开启“朋友圈转发”与“小视频30秒”两个功能开关。

## 语音功能

- 点歌
  - 个人点歌
  - 指定群点歌
  - 点歌来源（网易云音乐、酷狗音乐、酷我音乐）
- 分享选项
- MP3转语音
- MP4转语音
- 分享音乐转语音
- 分享音乐转文件
- 短视频转语音 | 朋友圈
  - 支持抖音、快手、皮皮虾中复制链接在聊天中粘贴发送即可
- 文字转语音
  - 支持命令，查看命令：#命令 或 #选择
  - 文字转语音字数限制最多 300 字
- 长按文字转语音
- 长按修改文字（自我安慰）
- 左滑文字转语音
  - **点歌、MP3 转语音、MP4 转语音、转发音乐、短视频链接转语音、文字转语音、长按或左滑文字转语音为收费功能。**
- 语言转文字
- 右滑文字引用
- 语音转发
- 转发收藏
- 语音+1
- 文字+1
- 表情+1
- 语音秒数
  - 所有语音秒数都会变成设置的秒数
- 语音秒数
  - 可设置发送语音秒数：1-60
- 语音包
  - 授权版本地语言包文件放至微信文档目录：/Library/Preferences/VoiceBao/新建文件夹/，支持语音包分类
  - 免费版本地语言包文件放至微信文档目录：/Library/Preferences/Voice/
- 语音包添加
- 语音包随机秒数
- 语音包试听
  - 首先发送一条语音给自己，长按改语音，点击试听，让第一条语音作为试听载体，发送语音前请先清空记录

## 动态视频

- 播放声音
- 选择视频
  - 从相册选择视频，或者视频文件放至微信文档目录：/Libray/Caches/，命名为 backgoup.mp4

## 获取授权码

- 微信「设置 - WeChat - 点击复制」；

![](https://files.mdnice.com/user/164/20ae1e39-21db-427a-812f-51c3f30679fd.png)

## 关于授权

1. 目前售价 ￥35，不排除后期运营、维护成本的增加而涨价；
2. 授权绑定微信号，支持切换设备登录；
3. 已授权用户，支持修改微信号；
4. 不支持换绑微信号；
5. 授权无时间限制，为买断制，非订阅制；
6. 授权完成后，半小时内不满意可以退款，超过半小时不接受任何理由退款。

## 兼容性

- Chimera/Odyssey/Taurine 越狱设备，需安装 libhooker Configurator 插件，设置 Jan WeChat 为 Substrate 兼容模式。

![](https://files.mdnice.com/user/164/8be352d2-5f78-438c-910d-ef477d2a59b8.JPEG)

> 如果在默认 libhooker 默认模式下出现使用某项功能导致微信闪退，请务必切换至 Substrate 兼容模式。设置完成后，请注销设备，以确保设置生效。

## 语言包下载

- 加 QQ 群：58128869，群文件下载使用。

##  购买授权

TG：[https://t.me/twjacy](https://t.me/twjacy)

![](https://files.mdnice.com/user/164/044478ed-f4f1-47ff-8c9c-40eeeae9f487.png)

WeChat：NTg4OTY1MA==（BASE64）

备用 WeChat：ZGV2Ym90（BASE64）

QQ：NTg4OTY1MA==（BASE64）

公众号：Jailbreaks

## 授权之后

- 上滑微信退出后台，再次进入；
- 插件开关都有相关功能说明，在开启之前请查看；
- 文字转语音开启后，请先设置人物以及语音秒数；

## 广而告之

**憨憨&亦欢 UDID 定制**

- 身边没有电脑，无法续签？
- 手机忘记续签，超过 7 天？
- 不仅仅是 UDID 定制，更是提供交流的平台；
- 包含掉签修复、后期更新维护、售后服务；
- 50/年（不排除随着市场价格波动）

![](https://files.mdnice.com/user/164/61cac610-2f94-47a1-a4fc-1f62adcad5f8.png)

![](https://files.mdnice.com/user/164/4813b140-6793-4c05-8530-0386f77756b3.png)
