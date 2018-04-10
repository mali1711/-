---
title: ECshop的基本使用
tags: 安装,后台的基本设置
grammar_cjkRuby: true
---


欢迎使用 **{小书匠}(xiaoshujiang)编辑器**，您可以通过==设置==里的修改模板来改变新建文章的内容。



## 安装
官网现在并且解压，将对应的文件复制到我们的php项目目录中去。

安装过程中基本的配置:

![enter description here][1]

## 各个文件夹的基本介绍
ECShop 最新程序 的结构图及各文件相应功能介绍
### ECShop文件结构目录
┣ activity.php 活动列表
┣ affiche.php 广告处理文件
┣ affiliate.php 生成商品列表
┣ article.php 文章内容
┣ article_cat.php文章分类
┣ auction.php 拍卖前台文件
┣ brand.php 品牌列表
┣ captcha.php 生成验证码
┣ catalog.php 列出所以分类及品牌
┣ category.php 商品分类
┣ comment.php 提交用户评论
┣ compare.php 商品比较程序
┣ cycle_image.php 轮播图片程序
┣ feed.php RSS Feed 生成程序
┣ flow.php 购物流程
┣ gallery.php 商品相册
┣ goods.php 商品详情
┣ goods_script.php 生成商品列表
┣ group_buy.php团购商品前台文件
┣ index.php 首页文件
┣ myship.php 支付配送DEMO
┣ pick_out.php 选购中心
┣ receive.php 处理收回确认的页面
┣ region.php 地区切换程序
┣ respond.php 支付响应页面
┣ robots.txt
┣ search.php 搜索程序
┣ sitemaps.php google sitemap 文件
┣ snatch.php 夺宝奇兵前台页面
┣ tag_cloud.php 标签云
┣ topic.php 专题前台
┣ user.php 会员中心
┣ vote.php 调查程序
┣ wholesale.php 批发前台文件
┣ admin文件夹
┃ ┣ account_log.php 管理中心帐户变动记录
┃ ┣ admin_logs.php 记录管理员操作日志
┃ ┣ ads.php 广告管理程序
┃ ┣ adsense.php 站外JS投放的统计程序
┃ ┣ ad_position.php广告位置管理程序
┃ ┣ affiliate.php 程序说明
┃ ┣ affiliate_ck.php 程序说明
┃ ┣ agency.php 管理中心办事处管理
┃ ┣ area_manage.php 地区列表管理文件
┃ ┣ article.php 管理中心文章处理程序文件
┃ ┣ articlecat.php 文章分类管理程序
┃ ┣ article_auto.php
┃ ┣ attention_list.php
┃ ┣ attribute.php 属性规格管理
┃ ┣ auction.php 管理中心拍卖活动管理
┃ ┣ bonus.php 红包类型的处理
┃ ┣ brand.php管理中心品牌管理
┃ ┣ captcha_manage.php
┃ ┣ card.php 贺卡管理程序
┃ ┣ category.php 商品分类管理程序
┃ ┣ check_file_priv.php 系统文件检测
┃ ┣ comment_manage.php 用户评论管理程序
┃ ┣ convert.php 转换程序
┃ ┣ cron.php 计划任务
┃ ┣ database.php 数据库管理
┃ ┣ ebao_commend.php 易宝推荐
┃ ┣ edit_languages.php 管理中心语言项编辑(前台语言项)
┃ ┣ email_list.php 邮件列表管理
┃ ┣ favourable.php 管理中心优惠活动管理
┃ ┣ flashplay.php
┃ ┣ flow_stats.php 综合流量统计
┃ ┣ friend_link.php 友情链接管理
┃ ┣ gen_goods_script.php 生成显示商品的js代码
┃ ┣ get_password.php 找回管理员密码
┃ ┣ goods.php 商品管理程序
┃ ┣ goods_auto.php
┃ ┣ goods_batch.php 商品批量上传、修改
┃ ┣ goods_booking.php 缺货处理管理程序
┃ ┣ goods_export.php
┃ ┣ goods_type.php 商品类型管理程序
┃ ┣ group_buy.php 管理中心团购商品管理
┃ ┣ guest_stats.php 客户统计
┃ ┣ index.php 控制台首页
┃ ┣ integrate.php 第三方程序会员数据整合插件管理程序
┃ ┣ magazine_list.php
┃ ┣ mail_template.php 管理中心模版管理程序
┃ ┣ message.php 管理中心管理员留言程序
┃ ┣ navigator.php
┃ ┣ order.php 订单管理
┃ ┣ order_stats.php 订单统计
┃ ┣ pack.php 包装管理程序
┃ ┣ payment.php 支付方式管理程序
┃ ┣ picture_batch.php 图片批量处理程序
┃ ┣ privilege.php 管理员信息以及权限管理程序
┃ ┣ sale_general.php 销售概况
┃ ┣ sale_list.php 销售明细列表程序
┃ ┣ sale_order.php 商品销售排行
┃ ┣ searchengine_stats.php 搜索引擎关键字统计
┃ ┣ search_log.php
┃ ┣ shipping.php 配送方式管理程序
┃ ┣ shipping_area.php 配送区域管理程序
┃ ┣ shophelp.php 帮助信息管理程序
┃ ┣ shopinfo.php 网店信息管理页面
┃ ┣ shop_config.php 管理中心商店设置
┃ ┣ sitemap.php 站点地图生成程序
┃ ┣ sms.php 短信模块 之 控制器
┃ ┣ snatch.php 夺宝奇兵管理程序
┃ ┣ sql.php sql管理程序
┃ ┣ tag_manage.php 后台标签管理
┃ ┣ template.php 管理中心模版管理程序
┃ ┣ topic.php 专题管理
┃ ┣ users.php 会员管理程序
┃ ┣ users_order.php 会员排行统计程序
┃ ┣ user_account.php 会员帐目管理(包括预付款，余额)
┃ ┣ user_msg.php 客户留言
┃ ┣ user_rank.php 会员等级管理程序
┃ ┣ view_sendlist.php
┃ ┣ virtual_card.php 虚拟卡商品管理程序
┃ ┣ visit_sold.php 访问购买比例
┃ ┣ vote.php 调查管理程序
┃ ┣ wholesale.php 管理中心批发管理
┃ ┣ help 的目录 后台操作帮助文件
┃ ┣ images 的目录
┃ ┣ includes 的目录
┃ ┃ ┣ cls_exchange.php 后台自动操作数据库的类文件
┃ ┃ ┣ cls_google_sitemap.php Google sitemap 类
┃ ┃ ┣ cls_phpzip.php ZIP 处理类
┃ ┃ ┣ cls_sql_dump.php 数据库导出类
┃ ┃ ┣ inc_menu.php 管理中心菜单数组
┃ ┃ ┣ init.php 管理中心公用文件
┃ ┃ ┣ lib_goods.php 管理中心商品相关函数
┃ ┃ ┣ lib_main.php 管理中心公用函数库
┃ ┃ ┗ lib_template.php 管理中心模版相关公用函数库
┃ ┣ styles 的目录
┃ ┣ templates 的目录
┃ ┗ js 的目录
┃ ┣ colorselector.js
┃ ┣ common.js
┃ ┣ listtable.js
┃ ┣ md5.js
┃ ┣ selectzone.js
┃ ┣ tab.js
┃ ┣ todolist.js
┃ ┣ topbar.js
┃ ┗ validator.js 表单验证类
┣ api 的目录
┃ ┣ checkorder.php 检查订单 API
┃ ┣ cron.php
┃ ┗ init.php API 公用初始化文件
┣ cert 的目录
┣ data 的目录
┃ ┣ ffiliate.html
┃ ┣ goods_script.html
┃ ┣ order_print.html
┃ ┣ afficheimg 的目录
┃ ┣ brandlogo 的目录
┃ ┣ captcha 的目录 验证码背景图片存放位置
┃ ┣ cardimg 的目录
┃ ┣ feedbackimg 的目录
┃ ┣ images 的目录
┃ ┣ packimg 的目录
┃ ┗ sqldata 的目录
┣ images 的目录
┃ ┗ upload 的目录
┃ ┣ File 文件上传存放处
┃ ┣ Flash flash上传存放处
┃ ┣ Image 图片上传存放处
┃ ┗ Media 视频上传存放处
┣ includes 的目录
┃ ┣ cls_captcha.php 验证码图片类
┃ ┣ cls_ecshop.php 基础类
┃ ┣ cls_error.php 用户级错误处理类
┃ ┣ cls_iconv.php 字符集转换类
┃ ┣ cls_image.php 后台对上传文件的处理类(实现图片上传，图片缩小， 增加水印)
┃ ┣ cls_json.php JSON 类
┃ ┣ cls_mysql.php MYSQL 公用类库
┃ ┣ cls_rss.php RSS 类
┃ ┣ cls_session.php SESSION 公用类库
┃ ┣ cls_sms.php 短信模块 之 模型（类库）
┃ ┣ cls_smtp.php SMTP 邮件类
┃ ┣ cls_sql_executor.php SQL语句执行类。
┃ ┣ cls_template.php 模版类
┃ ┣ cls_transport.php 服务器之间数据传输器
┃ ┣ inc_constant.php 常量
┃ ┣ init.php 前台公用文件
┃ ┣ lib.debug.php
┃ ┣ lib_article.php 文章及文章分类相关函数库
┃ ┣ lib_clips.php ECSHOP 用户相关函数库
┃ ┣ lib_code.php 加密解密类
┃ ┣ lib_common.php 公用函数库
┃ ┣ lib_goods.php 商品相关函数库
┃ ┣ lib_insert.php 动态内容函数库
┃ ┣ lib_main.php 前台公用函数库
┃ ┣ lib_order.php 购物流程函数库
┃ ┣ lib_passport.php 用户帐号相关函数库
┃ ┣ lib_payment.php 支付接口函数库
┃ ┣ lib_time.php 时间函数
┃ ┣ lib_transaction.php ECSHOP 用户交易相关函数库
┃ ┣ codetable 的目录
┃ ┃ ┣ big5-gb.table
┃ ┃ ┣ big5_utf8.php
┃ ┃ ┣ gb-big5.table
┃ ┃ ┣ gb_utf8.php
┃ ┃ ┗ ipdata.dat
┃ ┣ fckeditor 的目录 fckeditor编辑器目录
┃ ┗ modules 的目录
┃ ┣ convert 的目录
┃ ┃ ┣ shopex46.php vshopex4.6转换程序插件
┃ ┃ ┗ shopex47.php shopex4.7转换程序插件
┃ ┣ cron 的目录
┃ ┃ ┣ auto_manage.php 自动上下架管理
┃ ┃ ┗ ipdel.php 定期删除
┃ ┣ integrates 的目录
┃ ┃ ┣ bmforum.php 会员数据处理类
┃ ┃ ┣ discuz.php
┃ ┃ ┣ discuz55.php
┃ ┃ ┣ dvbbs.php
┃ ┃ ┣ ecshop.php
┃ ┃ ┣ integrate.php
┃ ┃ ┣ ipb.php
┃ ┃ ┣ molyx.php
┃ ┃ ┣ phpbb.php
┃ ┃ ┣ phpwind.php
┃ ┃ ┣ phpwind5.php
┃ ┃ ┗ vbb.php
┃ ┣ payment 的目录
┃ ┃ ┣ alipay.php 支付宝插件
┃ ┃ ┣ balance.php 余额支付插件
┃ ┃ ┣ bank.php 银行汇款（转帐）插件
┃ ┃ ┣ cappay.php 首信易支付插件
┃ ┃ ┣ chinabank.php 网银在线插件
┃ ┃ ┣ cncard.php 云网支付插件
┃ ┃ ┣ cod.php 货到付款插件
┃ ┃ ┣ ctopay.php Ctopay 支付插件
┃ ┃ ┣ express.php express支付系统插件
┃ ┃ ┣ ips.php ips支付系统插件
┃ ┃ ┣ kuaiqian.php 快钱插件
┃ ┃ ┣ nps.php NPS支付插件
┃ ┃ ┣ pay800.php 800pay 支付宝插件
┃ ┃ ┣ paypal.php 贝宝插件
┃ ┃ ┣ paypalcn.php 贝宝中国插件
┃ ┃ ┣ post.php 邮局汇款插件
┃ ┃ ┣ tenpay.php 财付通插件
┃ ┃ ┣ udpay.php 网汇通插件
┃ ┃ ┣ xpay.php 易付通插件
┃ ┃ ┗ yeepay.php YeePay易宝插件
┃ ┗ shipping 的目录
┃ ┣ cac.php 上门取货插件
┃ ┣ city_express.php 城际快递插件
┃ ┣ ems.php EMS插件
┃ ┣ flat.php 邮政包裹插件
┃ ┣ fpd.php 到付运费插件
┃ ┣ post_express.php 邮政包裹插件
┃ ┣ post_mail.php 邮局平邮插件
┃ ┣ presswork.php 挂号印刷品插件
┃ ┣ sf_express.php 顺丰速运 配送方式插件
┃ ┣ sto_express.php 申通快递 配送方式插件
┃ ┣ yto.php 圆通速递插件
┃ ┗ zto.php 中通速递插件
┣ install 的目录 安装文件目录
┣ js 的目录
┃ ┣ auto_complete.js
┃ ┣ calendar.php
┃ ┣ common.js
┃ ┣ compare.js
┃ ┣ global.js
┃ ┣ lefttime.js
┃ ┣ myship.js
┃ ┣ region.js
┃ ┣ shopping_flow.js
┃ ┣ transport.js
┃ ┣ user.js
┃ ┣ utils.js
┃ ┗ calendar 的目录
┣ languages 的目录 语言风格文件
┃ ┣ zh_cn 的目录
┃ ┃ ┣
┃ ┃ ┣ admin 的目录
┃ ┃ ┣ convert 的目录
┃ ┃ ┣ cron 的目录
┃ ┃ ┣ payment 的目录
┃ ┃ ┗ shipping 的目录
┃ ┗ zh_tw 的目录
┃ ┣ admin 的目录
┃ ┣ convert 的目录
┃ ┣ cron 的目录
┃ ┣ payment 的目录
┃ ┗ shipping 的目录
┣ plugins 的目录
┣ templates 的目录
┃ ┣ backup 的目录
┃ ┃ ┗ ibrary 的目录
┃ ┣ caches 的目录
┃ ┗ compiled 的目录
┃ ┗ admin 的目录
┣ themes 的目录
┃ ┣ default 的目录
┃ ┃ ┣ images 的目录
┃ ┃ ┗ library 的目录
┃ ┗ sport 的目录
┣ wap 的目录
┃ ┣ article.php
┃ ┣ brands.php
┃ ┣ buy.php
┃ ┣ category.php
┃ ┣ comment.php
┃ ┣ goods.php
┃ ┣ goods_list.php
┃ ┣ index.php
┃ ┣ user.php
┃ ┣ includes 的目录
┃ ┃ ┣ init.php
┃ ┃ ┣ lib_main.php
┃ ┗ templates 的目录
┃ ┣ article.wml
┃ ┣ article_list.wml
┃ ┣ brands.wml
┃ ┣ buy.wml
┃ ┣ category.wml
┃ ┣ comment.wml
┃ ┣ goods.wml
┃ ┣ goods_img.wml
┃ ┣ goods_list.wml
┃ ┣ index.wml
┃ ┣ login.wml
┃ ┣ order_list.wml
┃ ┗ user.wml
┗ widget 的目录
┣ blog_sohu.php
┣ blog_sohu.xhtml
┗ images 的目录

### 各个表结构

#### **ecs_account_log** 用户帐号情况记录表，包括资金和积分等

log_id mediumint 自增ID号
user_id mediumint 用户登录后保存在session中的id号，跟users表中的user_id对应
user_money decimal 用户该笔记录的余额
frozen_money decimal 被冻结的资金
rank_points mediumint 等级积分，跟消费积分是分开的
pay_points mediumint 消费积分，跟等级积分是分开的
change_time int 该笔操作发生的时间
change_desc varchar 该笔操作的备注，一般是，充值或者提现。也可是是管理员后台写的任何在备注
change_type tinyint 操作类型，0为充值，1为提现，2为管理员调节，99为其他类型

 

#### **ecs_ad** 广告列表配置表，包括站内站外的图片，文字，flash，代码广告

ad_id smallint 自增ID号
position_id smallint 0,站外广告；从1开始代表的是该广告所处的广告位，同表ad_position中的字段position_id的值
media_type tinyint 广告类型，0，图片；1，flash;2, 代码；3，文字
ad_name varchar 该条广告记录的广告名称
ad_link varchar 广告链接地址
ad_code text 广告链接的表现，文字广告就是文字或图片和flash就是它们的地址，代码广告就是代码内容
start_time int 广告开始时间
end_time int 广告结束时间
link_man varchar 广告联系人
link_email varchar 广告联系人的邮箱
link_phone varchar 广告联系人的电话
click_count mediumint 该广告点击数
enabled tinyint 该广告是否关闭，1，开启；0，关闭；关闭后广告将不再有效，直至重新开启

 

**ecs_ad_position** 广告位置配置表

position_id tinyint 广告位自增id
position_name varchar 广告位名称
ad_width smallint 广告位宽度
ad_height smallint 广告位高度
position_desc varchar 广告位描述
position_style text 广告位模板代码

 

**ecs_admin_action** 管理员权限列表树

action_id tinyint 自增ID号
parent_id tinyint 该id项的父id，对应本表的 action_id字段
action_code varchar 代表权限的英文字符串，对应汉文在语言文件中，如果该字段有某个字符串，就表示有该权限

 

**ecs_admin_log** 管理员操作日志表

log_id int 自增ID号
log_time int 写日志时间
user_id tinyint 该日志所记录的操作者id，同 ecs_admin_user的user_id
log_info varchar 管理操作内容
ip_address varchar 管理者登录ip

 

**ecs_admin_message** 管理员留言记录表

message_id smallint 自增ID号
sender_id tinyint 发送该留言的管理员id，同 ecs_admin_user的user_id
receiver_id tinyint 接收消息的管理员id，同 ecs_admin_user的user_id，如果是给多个管理员发送，则同一个消息给每个管理员id发送一条
sent_time int 留言发送时间
read_time int 留言阅读时间
readed tinyint 留言是否阅读，1，已阅读；0，未阅读
deleted tinyint 留言是否已经是否已经被删除，1，已删除；0，未删除
title varchar 留言的主题
message text 留言的内容

 

**ecs_admin_user** 管理员资料权限列表

user_id smallint 自增ID号，管理员代号
user_name varchar 管理员登录名
email varchar 管理员邮箱
password varchar 管理员登录秘密加密串
add_time int 管理员添加时间
last_login int 管理员最后一次登录时间
last_ip varchar 管理员最后一次登录ip
action_list text 管理员管理权限列表
nav_list text 管理员导航栏配置项
lang_type varchar
agency_id smallint 该管理员负责的办事处的id，同ecs_agency的 agency_id字段。如果管理员没负责办事处，则此处为0
todolist longtext 记事本记录的数据

 

**ecs_adsense** 广告点击率统计表

from_ad smallint 广告代号，-1是站外广告，如果是站内广告则为ecs_ad的ad_id
referer varchar 页面来源
clicks int 点击率

**ecs_affiliate_log** 分成相关的表，还没研究透

log_id mediumint
order_id mediumint
time int
user_id mediumint
user_name varchar
money decimal
point int
separate_type tinyint

**ecs_agency** 办事处信息

agency_id smallint 办事处ID
agency_name varchar 办事处名字
agency_desc text 办事处描述

ecs_area_region 记录表ecs_shipping_area中的 shipping_area_name的地区名包括ec

shipping_area_id smallint 配送区域的id号，等同于 ecs_shipping_area的shipping_area_id的值
region_id smallint 地区列表，等同于ecs_region的 region_id

**ecs_article** 文章内容表

article_id mediumint 自增ID号
cat_id smallint 该文章的分类，同ecs_article_cat的cat_id,如果不在，将自动成为保留类型而不能删除
title varchar 文章题目
content longtext 文章内容
author varchar 文章作者
author_email varchar 文章作者的email
keywords varchar 文章的关键字
article_type tinyint 文章类型，0，普通；1，置顶； 2和大于2的，为保留文章，保留文章不能删除
is_open tinyint 是否显示。1，显示；0，不显示
add_time int 文章添加时间
file_url varchar 上传文件或者外部文件的url
open_type tinyint 0,正常；当该字段为1或者2时，会在文章最后添加一个链接“相关下载”，连接地址等于file_url的值；但程序在此处有bug
link varchar 该文章标题所引用的连接，如果该项有值将不能显示文章内容，即该表中content的值

**ecs_article_cat** 文章分类信息表

cat_id smallint 自增ID号
cat_name varchar 分类名称
cat_type tinyint 分类类型；1，普通分类；2，系统分类；3，网店信息；4，帮助分类；5，网店帮助
keywords varchar 分类关键字
cat_desc varchar 分类说明文字
sort_order tinyint 分类显示顺序
show_in_nav tinyint 是否在导航栏显示；0，否；1，是
parent_id smallint 父节点id，取值于该表cat_id字段

**ecs_attribute** 商品类型属性表，该表记录的是每个商品类型的所有属性的配置情

attr_id smallint 自增ID号
cat_id smallint 商品类型，同ecs__type的cat_id
attr_name varchar 属性名称
attr_input_type tinyint 当添加商品时，该属性的添加类别；0，为手工输入；1，为选择输入；2，为多行文本输入
attr_type tinyint 属性是否多选；0，否；1，是；如果可以多选，则可以自定义属性，并且可以根据值的不同定不同的价
attr_values text 如果attr_input_type为1，即选择输入，则attr_name对应的值的取值就是该字段的值
attr_index tinyint 属性是否可以检索；0，不需要检索；1，关键字检索；2，范围检索；该属性应该是如果检索的话，可以通过该属性找到有该属性的商品
sort_order tinyint 属性显示的顺序，数字越大越靠前，如果数字一样则按id顺序
is_linked tinyint 是否关联；0，不关联；1，关联；如果关联，那么用户在购买该商品时，具有有该属性相同值的商品将被推荐给用户
attr_group tinyint 属性分组，相同的为一个属性组。该值应该取自ecs_goods_type的attr_group的值的顺序

**ecs_auction_log** 拍卖出价记录信息表

log_id mediumint 自增ID号
act_id mediumint 拍卖活动的id，取值于ecs_goods_activity的 act_id字段
bid_user mediumint 出价的用户id，取值于ecs_users的user_id
bid_price decimal 出价价格
bid_time int 出价时间

ecs_auto_manage 处理文章，商品自动上下线的计划任务列表；需要安装计划任务插

item_id mediumint 如果是商品就是ecs_goods的goods_id，如果是文章就是 ecs_article的article_id
type varchar goods是商品，article是文章
starttime int 上线时间
endtime int 下线时间

**ecs_bonus_type** 红包类型表

type_id smallint 红包类型流水号
type_name varchar 红包名称
type_money decimal 红包所值的金额
send_type tinyint 红包发送类型.0,按用户如会员等级 ,会员名称发放;1,按商品类别发送;2,按订单金额所达到的额度发送;3,线下发送
min_amount decimal 如果是按金额发送红包,该项是最小金额.即只要购买超过该金额的商品都可以领到红包
max_amount decimal
send_start_date int 红包发送的开始时间
send_end_date int 红包发送的结束时间
use_start_date int 红包可以使用的开始时间
use_end_date int 红包可以使用的结束时间
min_goods_amount decimal 可以使用该红包的商品的最低价格.即只要达到该价格的商品才可以使用红包

**ecs_booking_goods** 缺货登记的订购和处理记录表

rec_id mediumint 自增ID号
user_id mediumint 登记该缺货记录的用户的id，取值 ecs_users的user_id
email varchar 页面填的用户的email，默认取值于ecs_users的email
link_man varchar 页面填的用户的姓名，默认取值于ecs_users的consignee
tel varchar 页面填的用户的电话，默认取值于ecs_users的tel
goods_id mediumint 缺货登记的商品id，取值于 ecs_goods的 goods_id
goods_desc varchar 缺货登记时留的订购描述
goods_number smallint 订购数量
booking_time int 缺货登记的时间
is_dispose tinyint 是否已经被处理
dispose_user varchar 处理该缺货登记的管理员用户名，取值于session,该 session取值于ecs_admin_user的user_name
dispose_time int 处理的时间
dispose_note varchar 处理时管理员留的备注

**ecs_brand** 商品品牌信息记录表

brand_id smallint 自增ID号
brand_name varchar 品牌名称
brand_logo varchar 上传的该品牌公司logo图片
brand_desc text 品牌描述
site_url varchar 品牌的网址
sort_order tinyint 品牌在前台页面的显示顺序，数字越大越靠后
is_show tinyint 该品牌是否显示，0，否；1，显示

ecs_card 贺卡的配置的信息

card_id tinyint 自增ID号
card_name varchar 贺卡名称
card_img varchar 贺卡图纸的名称
card_fee decimal 贺卡所需费用
free_money decimal 订单达到该字段的值后使用此贺卡免费
card_desc varchar 贺卡的描述

ecs_cart 购物车购物信息记录表

rec_id mediumint 自增ID号
user_id mediumint 用户登录id，取自session，
session_id char 登录的sessionid，如果该用户退出，该sessionid对应的购物车中的所有记录都将被删除
goods_id mediumint 商品的id，取自表goods的 goods_id
goods_sn varchar 商品的货号，取自表goods的goods_sn
goods_name varchar 商品的名称，取自表goods的goods_name
market_price decimal 商品的市场价，取自表 goods的market_price
goods_price decimal 商品的本店价，取自表goods的 shop_price
goods_number smallint 商品的购买数量，在购物车时，实际库存不减少
goods_attr text 商品的属性，中括号里是该属性特有的价格
is_real tinyint 取自ecs_goods的is_real
extension_code varchar 商品的扩展属性，取自ecs_goods的 extension_code
parent_id mediumint 该商品的父商品id，没有该值为0 ，有的话那该商品就是该id的配件
rec_type tinyint 购物车商品类型，0，普通；1，团够；2，拍卖；3，夺宝奇兵
is_gift smallint 是否是赠品，0，否；其他，是参加优惠活动的id，取值于ecs_favourable_activity 的act_id
can_handsel tinyint
goods_attr_id mediumint 该商品的属性的id，取自goods_attr的 goods_attr_id，如果有多个，只记录了最后一个，可能是个bug

ecs_category 商品分类表，记录商品分类信息

cat_id smallint 自增ID号
cat_name varchar 分类名称
keywords varchar 分类的关键字，可能是为了搜索
cat_desc varchar 分类描述
parent_id smallint 该分类的父id，取值于该表的 cat_id字段
sort_order tinyint 该分类在页面显示的顺序，数字越大顺序越靠后；同数字，id在前的先显示
template_file varchar 不确定字段，按名字和表设计猜，应该是该分类的单独模板文件的名字
measure_unit varchar 该分类的计量单位
show_in_nav tinyint 是否显示在导航栏，0，不；1，显示在导航栏
style varchar 该分类的单独的样式表的包括文件名部分的文件路径
is_show tinyint 是否在前台页面显示，1，显示；0，不显示
grade tinyint 该分类的最高和最低价之间的价格分级，当大于1 时，会根据最大最小价格区间分成区间，会在页面显示价格范围，如0-300,300-600,600-900这种
filter_attr smallint 如果该字段有值，则该分类将还会按照该值对应在表goods_attr的goods_attr_id所对应的属性筛选，如，封面颜色下有红，黑分类筛选

ecs_collect_goods 会员收藏商品的记录列表，一条记录一个收藏商品

rec_id mediumint 收藏记录的自增id
user_id mediumint 该条收藏记录的会员id，取值于 ecs_users的user_id
goods_id mediumint 收藏的商品id，取值于ecs_goods 的goods_id
add_time int 收藏时间
is_attention tinyint 是否关注该收藏商品，1，是；0，否

ecs_comment 用户对文章和产品的评论列表

comment_id int 用户评论的自增id
comment_type tinyint 用户评论的类型；0，评论的是商品；1，评论的是文章
id_value mediumint 文章或者商品的id，文章对应的是 ecs_article 的article_id；商品对应的是ecs_goods的goods_id
email varchar 评论时提交的email地址，默认取的ecs_users的email
user_name varchar 评论该文章或商品的人的名称，取值ecs_users的 user_name
content text 评论的内容
comment_rank tinyint 该文章或者商品的星级；只有1 到5星；由数字代替；其中5是代表5星
add_time int 评论的时间
ip_address varchar 评论时的用户ip
status tinyint 是否被管理员批准显示，1，是；0，未批准显示
parent_id int 评论的父节点；取值该表的comment_id 字段；如果该字段为0，则是一个普通评论，否则该条评论就是该字段的值所对应的评论的回复
user_id int 发表该评论的用户的用户id，取值于 ecs_users的user_id

ecs_crons 计划任务插件安装配置信息

cron_id tinyint 自增ID号
cron_code varchar 该插件文件在相应路径下的不包括”.php”部分的文件名，运行该插件将通过该字段的值寻找将运行的文件
cron_name varchar 计划任务的名称
cron_desc text 计划人物的描述
cron_order tinyint 应该是用了设置计划任务执行的顺序的，即当同时触发2个任务时先执行哪一个，如果一样应该是id在前的先执行暂不确定
cron_config text 对每次处理的数据的数量的值，类型，名称序列化；比如删几天的日志，每次执行几个商品或文章的处理
thistime int 该计划任务上次被执行的时间
nextime int 该计划任务下次被执行的时间
day tinyint 如果该字段有值，则计划任务将在每月的这一天执行该计划人物
week varchar 如果该字段有值，则计划任务将在每周的这一天执行该计划人物
hour varchar 如果该字段有值，则该计划任务将在每天的这个小时段执行该计划任务
minute varchar 如果该字段有值，则该计划任务将在每小时的这个分钟段执行该计划任务，该字段的值可以多个，用空格间隔
enable tinyint 该计划任务是否开启；0，关闭；1，开启
run_once tinyint 执行后是否关闭，这个关闭的意思还得再研究下
allow_ip varchar 允许运行该计划人物的服务器ip
alow_files varchar 运行触发该计划人物的文件列表可多个值，为空代表所有许可的文件都可以

ecs_email_list 增加电子杂志订阅表

id mediumint 邮件订阅的自增id
email varchar 邮件订阅所填的邮箱地址
stat tinyint 是否确认，可以用户确认也可以管理员确认；0，未确认；1，已确认
hash varchar 邮箱确认的验证码，系统生成后发送到用户邮箱，用户验证激活时通过该值判断是否合法；主要用来防止非法验证邮箱

ecs_email_sendlist 增加发送队列表

id mediumint 邮件发送队列自增id
email varchar 该邮件将要发送到的邮箱地址
template_id mediumint 该邮件的模板id，取值于ecs_mail_templates的 template_id
email_content text 邮件发送的内容
error tinyint 错误次数，不知干什么用的，猜应该是发送邮件的失败记录
pri tinyint 该邮件发送的优先级；0，普通；1，高
last_send int 上一次发送的时间

ecs_error_log 该表用来记录页面触发计划任务时失败所产生的错误，从程序来看

id int 计划任务错误自增id
info varchar 错误详细信息
file varchar 产生错误的执行文件的绝对路径
time int 错误发生的时间

ecs_favourable_activity 优惠活动的配置信息，优惠活动包括送礼，减免，打折

act_id smallint 优惠活动的自增id
act_name varchar 优惠活动的活动名称
start_time int 活动的开始时间
end_time int 活动的结束时间
user_rank varchar 可以参加活动的用户信息，取值于ecs_user_rank的 rank_id；其中0是非会员，其他是相应的会员等级；多个值用逗号分隔
act_range tinyint 优惠范围；0，全部商品；1，按分类；2，按品牌；3，按商品
act_range_ext varchar 根据优惠活动范围的不同，该处意义不同；但是都是优惠范围的约束；如，如果是商品，该处是商品的id，如果是品牌，该处是品牌的id
min_amount decimal 订单达到金额下限，才参加活动
max_amount decimal 参加活动的订单金额下限，0，表示没有上限
act_type tinyint 参加活动的优惠方式；0，送赠品或优惠购买；1，现金减免；价格打折优惠
act_type_ext decimal 如果是送赠品，该处是允许的最大数量，0 ，无数量限制；现今减免，则是减免金额，单位元；打折，是折扣值，100算，8折就是80
gift text 如果有特惠商品，这里是序列化后的特惠商品的id,name,price信息;取值于ecs_goods的goods_id，goods_name，价格是添加活动时填写的
sort_order tinyint 活动在优惠活动页面显示的先后顺序，数字越大越靠后

ecs_feedback 用户反馈信息表，包括留言，投诉，咨询等

msg_id mediumint 反馈信息自增id
parent_id mediumint 父节点，取自该表msg_id；反馈该值为0；回复反馈为节点id
user_id mediumint 反馈的用户的id
user_name varchar 反馈的用户的用户名
user_email varchar 反馈的用户的邮箱
msg_title varchar 反馈的标题，回复为reply
msg_type tinyint 反馈的类型，0，留言；1，投诉；2 ，询问；3，售后；4，求购
msg_content text 反馈的内容
msg_time int 反馈的时间
message_img varchar 用户上传的文件的地址
order_id int 该反馈关联的订单id，由用户提交，取值于 ecs_order_info的order_id；0，为无匹配；

ecs_friend_link 友情链接配置信息表

link_id smallint 友情链接自增id
link_name varchar 友情链接的名称，img的alt的内容;
link_url varchar 友情链接网站的链接地址
link_logo varchar 友情链接的logo
show_order tinyint 在页面的显示顺序

ecs_goods 商品表

goods_id mediumint 商品的自增id
cat_id smallint 商品所属商品分类id，取值 ecs_category的cat_id
goods_sn varchar 商品的唯一货号
goods_name varchar 商品的名称
goods_name_style varchar 商品名称显示的样式；包括颜色和字体样式；格式如#ff00ff+strong
click_count int 商品点击数
brand_id smallint 品牌id，取值于ecs_brand 的 brand_id
provider_name varchar 供货人的名称，程序还没实现该功能
goods_number smallint 商品库存数量
goods_weight decimal 商品的重量，以千克为单位
market_price decimal 市场售价
shop_price decimal 本店售价
promote_price decimal 促销价格
promote_start_date int 促销价格开始日期
promote_end_date int 促销价结束日期
warn_number tinyint 商品报警数量
keywords varchar 商品关键字，放在商品页的关键字中，为搜索引擎收录用
goods_brief varchar 商品的简短描述
goods_desc text 商品的详细描述
goods_thumb varchar 商品在前台显示的微缩图片，如在分类筛选时显示的小图片
goods_img varchar 商品的实际大小图片，如进入该商品页时介绍商品属性所显示的大图片
original_img varchar 应该是上传的商品的原始图片
is_real tinyint 是否是实物，1，是；0，否；比如虚拟卡就为0，不是实物
extension_code varchar 商品的扩展属性，比如像虚拟卡
is_on_sale tinyint 该商品是否开放销售，1，是；0，否
is_alone_sale tinyint 是否能单独销售，1，是；0，否；如果不能单独销售，则只能作为某商品的配件或者赠品销售
integral int 购买该商品可以使用的积分数量，估计应该是用积分代替金额消费；但程序好像还没有实现该功能
add_time int 商品的添加时间
sort_order smallint 应该是商品的显示顺序，不过该版程序中没实现该功能
is_delete tinyint 商品是否已经删除，0，否；1，已删除
is_best tinyint 是否是精品；0，否；1，是
is_new tinyint 是否是新品；0，否；1，是
is_hot tinyint 是否热销，0，否；1，是
is_promote tinyint 是否特价促销；0，否；1，是
bonus_type_id tinyint 购买该商品所能领到的红包类型
last_update int 最近一次更新商品配置的时间
goods_type smallint 商品所属类型id，取值表 goods_type的cat_id
seller_note varchar 商品的商家备注，仅商家可见
give_integral int 购买该商品时每笔成功交易赠送的积分数量。

ecs_goods_activity 拍卖活动和夺宝奇兵活动配置信息表

act_id mediumint 自增ID号
act_name varchar 促销活动的名称
act_desc text 促销活动的描述
act_type tinyint
goods_id mediumint 参加活动的id，取值于ecs_goods的goods_id
goods_name varchar 商品的名称，取值于ecs_goods的goods_id
start_time int 活动开始时间
end_time int 活动结束时间
is_finished tinyint 活动是否结束，0，结束；1，未结束
ext_info text 序列化后的促销活动的配置信息，包括最低价，最高价，出价幅度，保证金等

ecs_goods_article 文章关联产品表，即文章中提到的相关产品

goods_id mediumint 商品id，取自ecs_goods的 goods_id
article_id mediumint 文章id，取自 ecs_article 的 article_id
admin_id tinyint 猜想是管理员的id，但是程序中似乎没有提及到

ecs_goods_attr 具体商品的属性表

goods_attr_id int 自增ID号
goods_id mediumint 该具体属性属于的商品，取值于 ecs_goods的goods_id
attr_id smallint 该具体属性属于的属性类型的id，取自ecs_attribute 的attr_id
attr_value text 该具体属性的值
attr_price varchar 该属性对应在商品原价格上要加的价格

ecs_goods_cat 商品的扩展分类

goods_id mediumint 商品id
cat_id smallint 商品分类id

ecs_goods_gallery 商品相册表，只出现在页面的商品相册中

img_id mediumint 商品相册自增id
goods_id mediumint 图片属于商品的id
img_url varchar 实际图片url
img_desc varchar 图片说明信息
thumb_url varchar 微缩图片url
img_original varchar 根据名字猜，应该是上传的图片文件的最原始的文件的url

ecs_goods_type 商品类型表，该表每条记录就是一个商品类型

cat_id smallint 自增ID号
cat_name varchar 商品类型名
enabled tinyint 类型状态，1，为可用；0为不可用；不可用的类型，在添加商品的时候选择商品属性将不可选
attr_group varchar 商品属性分组，将一个商品类型的属性分成组，在显示的时候也是按组显示。该字段的值显示在属性的前一行，像标题的作用


ecs_group_goods 该表应该是商品配件配置表

parent_id mediumint 父商品id
goods_id mediumint 配件商品id
goods_price decimal 配件商品的价格
admin_id tinyint 添加该配件的管理员的id

ecs_keywords 页面搜索关键字搜索记录

date date 搜索日期
searchengine varchar 搜索引擎，默认是ecshop
keyword varchar 搜索关键字，即用户填写的搜索内容
count mediumint 搜索次数，按天累加

ecs_link_goods 关联商品信息表，关联商品是什么意思还没研究明白

goods_id mediumint 商品id
link_goods_id mediumint 被关联的商品的id
is_double tinyint 是否是双向关联；0，否；1，是
admin_id tinyint 添加此关联商品信息的管理员id

ecs_mail_templates 各种邮件的模板配置模板包括杂志模板

template_id tinyint 邮件模板自增id
template_code varchar 模板字符串名称，主要用于插件言语包时匹配语言包文件等用途
is_html tinyint 邮件是否是html格式；0，否；1，是
template_subject varchar 该邮件模板的邮件主题
template_content text 邮件模板的内容
last_modify int 最后一次修改模板的时间
last_send int 最近一次发送的时间，好像仅在杂志才记录
type varchar 该邮件模板的邮件类型；共2个类型；magazine，杂志订阅； template，关注订阅

ecs_member_price 商品不按照会员的折扣定价，而是再单独为不同的会员等级定的价

price_id mediumint 折扣价自增id
goods_id mediumint 商品的id
user_rank tinyint 会员登记id
user_price decimal 指定商品对指定会员等级的固定定价价格，单位元

ecs_nav 上中下3个导航栏的显示配置

id mediumint 导航配置自增id
ctype varchar
cid smallint
name varchar 导航显示标题
ifshow tinyint 是否显示
vieworder tinyint 页面显示顺序，数字越大越靠后
opennew tinyint 导航链接页面是否在新窗口打开，1，是；其他，否
url varchar 链接的页面地址
type varchar 处于导航栏的位置，top为顶部；middle为中间；bottom,为底部

ecs_order_action 对订单操作日志表

action_id mediumint 流水号
order_id mediumint 被操作的交易号
action_user varchar 操作该次的人员
order_status tinyint 作何操作.0，未确认；1，已确认；2，已取消；3，无效；4，退货；
shipping_status tinyint 发货状态。0，未发货；1，已发货；2，已收货；3，备货中
pay_status tinyint 支付状态.0,未付款;1,付款中;2, 已付款;
action_note varchar 操作备注
log_time int 操作时间

ecs_order_goods 订单的商品信息，注：订单的商品信息基本都是从购物车所对应的

rec_id mediumint 订单商品信息自增id
order_id mediumint 订单商品信息对应的详细信息id，取值order_info的order_id
goods_id mediumint 商品的的id，取值表ecs_goods 的 goods_id
goods_name varchar 商品的名称，取值表ecs_goods
goods_sn varchar 商品的唯一货号，取值ecs_goods
goods_number smallint 商品的购买数量
market_price decimal 商品的市场售价，取值ecs_goods
goods_price decimal 商品的本店售价，取值ecs_goods
goods_attr text 购买该商品时所选择的属性；
send_number smallint 当不是实物时，是否已发货，0 ，否；1，是
is_real tinyint 是否是实物，0，否；1，是；取值 ecs_goods
extension_code varchar 商品的扩展属性，比如像虚拟卡。取值ecs_goods
parent_id mediumint 父商品id，取值于ecs_cart的 parent_id；如果有该值则是值多代表的物品的配件
is_gift smallint 是否参加优惠活动，0，否；其他，取值于ecs_cart 的is_gift，跟其一样，是参加的优惠活动的id

ecs_order_info 订单的配送，贺卡等详细信息

order_id mediumint 订单详细信息自增id
order_sn varchar 订单号，唯一
user_id mediumint 用户id，同ecs_users的user_id
order_status tinyint 订单状态。0，未确认；1，已确认；2，已取消；3，无效；4，退货；
shipping_status tinyint 商品配送情况，0，未发货； 1，已发货；2，已收货；3，备货中
pay_status tinyint 支付状态；0，未付款；1，付款中；2，已付款
consignee varchar 收货人的姓名，用户页面填写，默认取值于表 user_address
country smallint 收货人的国家，用户页面填写，默认取值于表user_address，其id对应的值在ecs_region
province smallint 收货人的省份，用户页面填写，默认取值于表user_address，其id对应的值在ecs_region
city smallint 收货人的城市，用户页面填写，默认取值于表user_address，其id对应的值在ecs_region
district smallint 收货人的地区，用户页面填写，默认取值于表user_address，其id对应的值在ecs_region
address varchar 收货人的详细地址，用户页面填写，默认取值于表 user_address
zipcode varchar 收货人的邮编，用户页面填写，默认取值于表 user_address
tel varchar 收货人的电话，用户页面填写，默认取值于表user_address
mobile varchar 收货人的手机，用户页面填写，默认取值于表user_address
email varchar 收货人的手机，用户页面填写，默认取值于表user_address
best_time varchar 收货人的最佳送货时间，用户页面填写，默认取值于表 user_address
sign_building varchar 收货人的地址的标志性建筑，用户页面填写，默认取值于表user_address
postscript varchar 订单附言，由用户提交订单前填写
shipping_id tinyint 用户选择的配送方式id，取值表 ecs_shipping
shipping_name varchar 用户选择的配送方式的名称，取值表ecs_shipping
pay_id tinyint 用户选择的支付方式的id，取值表ecs_payment
pay_name varchar 用户选择的支付方式的名称，取值表ecs_payment
how_oos varchar 缺货处理方式，等待所有商品备齐后再发； 取消订单；与店主协商
how_surplus varchar 根据字段猜测应该是余额处理方式，程序未作这部分实现
pack_name varchar 包装名称，取值表ecs_pack
card_name varchar 贺卡的名称，取值ecs_card
card_message varchar 贺卡内容，由用户提交
inv_payee varchar 发票抬头，用户页面填写
inv_content varchar 发票内容，用户页面选择，取值ecs_shop_config的 code字段的值为invoice_content的value
goods_amount decimal 商品总金额
shipping_fee decimal 配送费用
insure_fee decimal 保价费用
pay_fee decimal 支付费用,跟支付方式的配置相关，取值表ecs_payment
pack_fee decimal 包装费用，取值表取值表ecs_pack
card_fee decimal 贺卡费用，取值ecs_card
money_paid decimal 已付款金额
surplus decimal 该订单使用余额的数量，取用户设定余额，用户可用余额，订单金额中最小者
integral int 使用的积分的数量，取用户使用积分，商品可用积分，用户拥有积分中最小者
integral_money decimal 使用积分金额
bonus decimal 使用红包金额
order_amount decimal 应付款金额
from_ad smallint 订单由某广告带来的广告id，应该取值于 ecs_ad
referer varchar 订单的来源页面
add_time int 订单生成时间
confirm_time int 订单确认时间
pay_time int 订单支付时间
shipping_time int 订单配送时间
pack_id tinyint 包装id，取值取值表ecs_pack
card_id tinyint 贺卡id，用户在页面选择，取值取值 ecs_card
bonus_id smallint 红包的id，ecs_user_bonus的 bonus_id
invoice_no varchar 发货单号，发货时填写，可在订单查询查看
extension_code varchar 通过活动购买的商品的代号；GROUP_BUY是团购； AUCTION，是拍卖；SNATCH，夺宝奇兵；正常普通产品该处为空
extension_id mediumint 通过活动购买的物品的id，取值ecs_goods_activity；如果是正常普通商品，该处为0
to_buyer varchar 商家给客户的留言,当该字段有值时可以在订单查询看到
pay_note varchar 付款备注，在订单管理里编辑修改
agency_id smallint 该笔订单被指派给的办事处的id，根据订单内容和办事处负责范围自动决定，也可以有管理员修改，取值于表ecs_agency
inv_type varchar 发票类型，用户页面选择，取值ecs_shop_config的code字段的值为invoice_type的value
tax decimal 发票税额
is_separate tinyint 0，未分成或等待分成；1，已分成；2，取消分成；
parent_id mediumint 能获得推荐分成的用户id，id取值于表ecs_users
discount decimal 折扣金额

ecs_pack 商品包装信息配置表

pack_id tinyint 包装配置的自增id
pack_name varchar 包装的名称
pack_img varchar 包装图纸
pack_fee smallint 包装的费用
free_money smallint 订单达到此金额可以免除该包装费用
pack_desc varchar 包装描述

ecs_pay_log 系统支付记录

log_id int 支付记录自增id
order_id mediumint 对应的交易记录的id，取值表 ecs_order_info
order_amount decimal 支付金额
order_type tinyint 支付类型；0，订单支付；1，会员预付款支付
is_paid tinyint 是否已支付，0，否；1，是

ecs_payment 安装的支付方式配置信息

pay_id tinyint 已安装的支付方式自增id
pay_code varchar 支付方式的英文缩写，其实就是该支付方式处理插件的不带后缀的文件名部分
pay_name varchar 支付方式名称
pay_fee varchar 支付费用
pay_desc text 支付方式描述
pay_order tinyint 支付方式在页面的显示顺序
pay_config text 支付方式的配置信息，包括商户号和密钥什么的
enabled tinyint 是否可用，0，否；1，是
is_cod tinyint 是否货到付款，0，否；1，是
is_online tinyint 是否在线支付，0，否；1，是

ecs_plugins

code varchar
version varchar
library varchar
assign tinyint
install_date int

ecs_region 地区列表

region_id smallint 表示该地区的id
parent_id smallint 该地区的上一个节点的地区id
region_name varchar 地区的名字
region_type tinyint 该地区的下一个节点的地区id
agency_id smallint 办事处的id,这里有一个bug,同一个省不能有多个办事处,该字段只记录最新的那个办事处的id

ecs_searchengine 搜索引擎访问记录

date date 搜索引擎访问日期
searchengine varchar 搜索引擎名称
count mediumint 访问次数

ecs_sessions session记录表

sesskey char sessionid,
expiry int session创建时间
userid mediumint 如果不是管理员，记录用户id
adminid mediumint 如果是管理员记录管理员id
ip char 客户端ip
data char 序列化后的session数据，如果session数据大于255则将数据存到表ecs_sessions_data，此处为空

ecs_sessions_data session数据表（超过255字节的session内容会保存在该表）

sesskey varchar sessionid
expiry int session创建时间
data longtext session序列化后的数据

ecs_shipping 配送方式配置信息表

shipping_id tinyint 自增ID号
shipping_code varchar 配送方式的字符串代号
shipping_name varchar 配送方式的名称
shipping_desc varchar 配送方式的描述
insure varchar 保价费用，单位元，或者是百分数，该值直接输出为报价费用
support_cod tinyint 是否支持货到付款，1，支持；0 ，不支持
enabled tinyint 该配送方式是否被禁用，1，可用；0 ，禁用

ecs_shipping_area 配送方式所属的配送区域和配送费用信息

shipping_area_id smallint 自增ID号
shipping_area_name varchar 配送方式中的配送区域的名字
shipping_id tinyint 该配送区域所属的配送方式，同 ecs_shipping的shipping_id
configure text 序列化的该配送区域的费用配置信息

ecs_shop_config 全站配置信息表

id smallint 全站配置信息自增id
parent_id smallint 父节点id，取值于该表id字段的值
code varchar 跟变量名的作用差不多，其实就是语言包中的字符串索引，如 $_LANG[cfg_range][cart_confirm]
type varchar 该配置的类型，text，文本输入框；password，密码输入框； textarea，文本区域；select，单选；options，循环生成多选；file,文件上传；manual，手动生成多选；group，是标题分组；hidden，不在页面显示
store_range varchar 当语言包中的code字段对应的是一个数组时，那该处就是该数组的索引，如$_LANG[cfg_range] [cart_confirm][1]；只有type字段为select,options 时才有值
store_dir varchar 当type为file时才有值，文件上传后的保存目录
value text 该项配置的值
sort_order tinyint 显示顺序，数字越大越靠后

ecs_snatch_log 夺宝奇兵出价记录表

log_id mediumint 自增ID号
snatch_id tinyint 夺宝奇兵活动号，取值于 ecs_goods_activity的act_id字段
user_id mediumint 出价的用户id，取值于ecs_users的 user_id
bid_price decimal 出价的价格
bid_time int 出价的时间

ecs_stats 访问信息记录表

access_time int 访问时间
ip_address varchar 访问者ip
visit_times smallint 访问次数，如果之前有过访问次数，在以前的基础上＋1
browser varchar 浏览器及版本
system varchar 操作系统
language varchar 语言
area varchar ip所在地区
referer_domain varchar 页面访问来源域名
referer_path varchar 页面访问来源除域名外的路径部分
access_url varchar 访问页面文件名

ecs_tag 商品的标记

tag_id mediumint 商品标签自增id
user_id mediumint 用户的id
goods_id mediumint 商品的id
tag_words varchar 标签内容

ecs_template 模板设置数据表

filename varchar 该条模板配置属于哪个模板页面
region varchar 该条模板配置在它所属的模板文件中的位置
library varchar 该条模板配置在它所属的模板文件中的位置处应该引入的lib 的相对目录地址
sort_order tinyint 模板文件中这个位置的引入lib项的值的显示顺序
id smallint 字段意义待查
number tinyint 每次显示多少个值
type tinyint 属于哪个动态项，0，固定项；1，分类下的商品；2，品牌下的商品；3，文章列表；4，广告位
theme varchar 该模板配置项属于哪套模板的模板名
remarks varchar 备注，可能是预留字段，没有值所以没确定用途

ecs_topic 专题活动配置表

topic_id int 专题自增id
title varchar 专题名称
intro text 专题介绍
start_time int 专题开始时间
end_time int 结束时间
data text 专题数据内容，包括分类，商品等
template varchar 专题模板文件
css text 专题样式代码

ecs_user_account 用户资金流动表，包括提现和充值

id mediumint 自增ID号
user_id mediumint 用户登录后保存在session中的id号，跟users表中的user_id对应
admin_user varchar 操作该笔交易的管理员的用户名
amount decimal 资金的数目，正数为增加，负数为减少
add_time int 记录插入时间
paid_time int 记录更新时间
admin_note varchar 管理员的被准
user_note varchar 用户的被准
process_type tinyint 操作类型，1，退款；0，预付费，其实就是充值
payment varchar 支付渠道的名称，取自payment的pay_name字段
is_paid tinyint 是否已经付款，０，未付；１，已付

ecs_user_address 收货人的信息表

address_id mediumint
address_name varchar
user_id mediumint 用户表中的流水号
consignee varchar 收货人的名字
email varchar 收货人的email
country smallint 收货人的国家
province smallint 收货人的省份
city smallint 收货人的城市
district smallint 收货人的地区
address varchar 收货人的详细地址
zipcode varchar 收货人的邮编
tel varchar 收货人的电话
mobile varchar 收货人的手机
sign_building varchar 收货地址的标志性建筑名
best_time varchar 收货人的最佳收货时间

ecs_user_bonus 已经发送的红包信息列表

bonus_id mediumint 红包的流水号
bonus_type_id tinyint 红包发送类型.0,按用户如会员等级,会员名称发放;1,按商品类别发送;2,按订单金额所达到的额度发送;3,线下发送
bonus_sn bigint 红包号,如果为0就是没有红包号.如果大于0,就需要输入该红包号才能使用红包
user_id mediumint 该红包属于某会员的id.如果为0,就是该红包不属于某会员
used_time int 红包使用的时间
order_id mediumint 使用了该红包的交易号
emailed tinyint 猜的，应该是是否已经将红包发送到用户的邮箱；1，是；0，否；

ecs_user_feed

feed_id mediumint
user_id mediumint
value_id mediumint
goods_id mediumint
feed_type tinyint
is_feed tinyint

ecs_user_rank 会员等级配置信息

rank_id tinyint 会员等级编号，其中0是非会员
rank_name varchar 会员等级名称
min_points int 该等级的最低积分
max_points int 该等级的最高积分
discount tinyint 该会员等级的商品折扣
show_price tinyint 是否在不是该等级会员购买页面显示该会员等级的折扣价格.1,显示;0,不显示
special_rank tinyint 是否事特殊会员等级组.0,不是;1,是

ecs_users

user_id mediumint 会员资料自增id
email varchar 会员邮箱
user_name varchar 用户名
password varchar 用户密码
question varchar 安全问题答案
answer varchar 安全问题
sex tinyint 性别，0，保密；1，男；2，女
birthday date 生日日期
user_money decimal 用户现有资金
frozen_money decimal 用户冻结资金
pay_points int 消费积分
rank_points int 会员等级积分
address_id mediumint 收货信息id，取值表 ecs_user_address
reg_time int 注册时间
last_login int 最后一次登录时间
last_time datetime 应该是最后一次修改信息时间，该表信息从其他表同步过来考虑
last_ip varchar 最后一次登录ip
visit_count smallint 登录次数
user_rank tinyint 会员登记id，取值ecs_user_rank
is_special tinyint
salt varchar
parent_id mediumint 推荐人会员id，
flag tinyint
alias varchar 昵称
msn varchar msn
qq varchar qq号
office_phone varchar 办公电话
home_phone varchar 家庭电话
mobile_phone varchar 手机
is_validated tinyint
credit_line decimal 信用额度，目前2.6.0版好像没有作实现

ecs_virtual_card 虚拟卡卡号库

card_id mediumint 虚拟卡卡号自增id
goods_id mediumint 该虚拟卡对应的商品id，取值于表 ecs_goods
card_sn varchar 加密后的卡号
card_password varchar 加密后的密码
add_date int 卡号添加日期
end_date int 卡号截至使用日期
is_saled tinyint 是否卖出，0，否；1，是
order_sn varchar 卖出该卡号的交易号，取值表ecs_order_info
crc32 int crc32后的key

ecs_vote 网站调查信息记录表

vote_id smallint 在线调查自增id
vote_name varchar 在线调查主题
start_time int 在线调查开始时间
end_time int 在线调查结束时间
can_multi tinyint 能否多选，0，可以；1，不可以
vote_count int 投票人数也可以说投票次数

ecs_vote_log 投票记录表

log_id mediumint 投票记录自增id
vote_id smallint 关联的投票主题id，取值表 ecs_vote
ip_address varchar 投票的ip地址
vote_time int 投票的时间

ecs_vote_option 投票的选项内容表

option_id smallint 投票选项自增id
vote_id smallint 关联的投票主题id，取值表 ecs_vote
option_name varchar 投票选项的值
option_count int 该选项的票数

ecs_wholesale 批发方案表

act_id mediumint 批发方案自增id
goods_id mediumint 商品id
goods_name varchar 商品名称
rank_ids varchar 适用会员登记，多个值之间用逗号分隔，取值于 ecs_user_rank
prices text 序列化后的商品属性，数量，价格
enabled tinyint 批发方案是否可用


## 后台的基础设置
### 网站店信息

### 基本设置

### 商品分类

### 首页广告管理

### 会员注册项设置

### 支付方式

### 配送方式

### 邮件服务器设置

### 模板的使用

### 数据库备份

## 使用自定义模板

### 1、前期准备
一个和ecshop 没有任何关系的html页面。

### 2、模板目录下的操作

 - 创建文件夹
 - 按照对应格式复制文件
 - 需要模板的样式再前台显示出来
 - style文件的操作

## 购物车代码的操作


  [1]: ./images/1521807952342.jpg "1521807952342.jpg"