# 📳 微信公众号每日定时自动推送

## 🎦 视频教学

### https://github.com/Ayron1929/wechat-auto-reminder/blob/main/demo.mp4
需要先下载

## 1️⃣ 申请测试号

### http://mp.weixin.qq.com/debug/cgi-bin/sandboxinfo?action=showinfo&t=sandbox/index
若有已认证的公众服务号，类似信息在👉基本配置👈中可以看到

## 2️⃣ 复制粘贴到测试号模版消息
今天是 {{date.DATA}}  

我们已经在一起了 {{love_day.DATA}} 天  
--> {{love_day_data.DATA}}

城市：{{region.DATA}}  
白天天气：{{weather_day_icon.DATA}} {{weather_day.DATA}}  
夜间天气：{{weather_night_icon.DATA}} {{weather_night.DATA}}  
最高气温：{{temp_max.DATA}}  
最低气温：{{temp_min.DATA}}

** {{birthday1_part1.DATA}}{{birthday1_part2.DATA}} **  
** {{birthday2_part1.DATA}}{{birthday2_part2.DATA}} **

“{{note_ch1.DATA}}{{note_ch2.DATA}}”  
"{{note_en1.DATA}}{{note_en2.DATA}}"  

## 3️⃣ 获取和风天气API Key

### https://id.qweather.com/
### 是KEY，不是Public ID！！！

## 4️⃣ 按需修改config.txt

## 🟡 还可以去天行数据申请别的接口

## ✅ Feedback
ayron1929@gmail.com
