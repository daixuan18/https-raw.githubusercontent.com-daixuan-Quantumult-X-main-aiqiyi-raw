# https-raw.githubusercontent.com-fmz200-wool_scripts-main-QuantumultX-rewrite-chongxie.txt
# > 爱奇艺
# hostname = -i.vip.iqiyi.com, *.iqiyi.com
# 播放页开通会员提示
^https?:\/\/act\.vip\.iqiyi\.com\/interact\/api\/v2\/show\? url reject-dict
# 首页信息流广告
^https?:\/\/[\d\.]+\/3f1\/cards\.iqiyi\.com\/(views_home\/3\.0\/qy_home|waterfall\/3\.0\/feed)\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/cnftp.js
^https?:\/\/access\.if\.iqiyi\.com\/3f1\/cards\.iqiyi\.com\/(views_category\/3\.0\/category_home|views_home\/3\.0\/qy_home|waterfall\/3\.0\/feed)\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/cnftp.js
^https?:\/\/cards\.iqiyi\.com\/views_category\/3\.0\/(category_home|categorylib_content|film_hybrid)\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/cnftp.js
^https?:\/\/cards\.iqiyi\.com\/(views_home\/3\.0\/qy_home|waterfall\/3\.0\/feed)\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/cnftp.js
# 播放详情页
^https?:\/\/cards\.iqiyi\.com\/views_plt\/3\.0\/player_tabs_v2\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/cnftp.js
# 搜索页列表
^https?:\/\/cards\.iqiyi\.com\/views_search\/3\.0\/(hot_query_)?search\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/cnftp.js
# 评论区
^https?:\/\/comment-card\.iqiyi\.com\/views_comment\/3\.0\/long_video_comments\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/cnftp.js
# 我的页面菜单
^https?:\/\/iface2\.iqiyi\.com\/aggregate\/3\.0\/getMyMenus\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/cnftp.js
# 首页左上角天气
^https?:\/\/iface2\.iqiyi\.com\/control\/3\.0\/init_proxy\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/cnftp.js
# 通用控制,各tab页二楼
^https?:\/\/iface2\.iqiyi\.com\/fusion\/3\.0\/common_switch\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/cnftp.js
# 播放页多余动效
^https?:\/\/iface2\.iqiyi\.com\/ivos\/interact\/video\/data\? url reject-dict
# 播放页升级白金会员按钮
^https?:\/\/iface2\.iqiyi\.com\/video\/3\.0\/v_interface_proxy\? url reject-dict
# 底部tab,顶部tab
^https?:\/\/iface2\.iqiyi\.com\/views\/3\.0\/(bottom_theme|home_top_menu)\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/cnftp.js
# 青少年弹窗
^https?:\/\/iface2\.iqiyi\.com\/views_pop\/3\.0\/pop_control\? url reject-dict
# 搜索框填充词
^https?:\/\/search\.video\.iqiyi\.com\/q\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/cnftp.js
# 开屏广告,播放广告
^https?:\/\/(kjp|t7z)\.cupid\.iqiyi\.com\/mixer\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/cnftp.js
