# -QF01
当前的测试项目
#从测试号信息获取
appID="wxc9188b9c3162dca4"
appSecret="4dde40389914eb31730e9598751eedac"
#收信人ID即 用户列表中的微信号，见上文
openId="oVUKivrnp1JGwvGKtrHcyLIpev-c"
#天气预报模板ID
weater_template_id=" 7Apj7gaR85DZYlVo3dFQrsrOaydT7Qct1jnDITjGYXk    蕞嗳的伱qr    今天；{{data.DATA}} 地区；{{region.DATA}} 天气；{{weather.DATA}} 气温；{{temp.DATA}} 风向；{{wind-dir.DATA}}"
#时间表模板ID
timetable_template_id="对你说的话；{{today-note.DATA}}"
schedule.every().day.at(07:00).do(weather_report,"南京")
schedule.every().monday.at("13:50").do(timetahble,"第二教学楼十分中后开始英语课")
whileTrue：
     schedule.tun_pending（）
     time.sleep（1）
     
