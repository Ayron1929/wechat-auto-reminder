# 微信公众号每日定时自动推送

## 视频教学

### 需要先下载 https://github.com/Ayron1929/wechat-auto-reminder/blob/main/demo.mp4

## ①申请测试号
个人公众号需要认证，相同信息👉基本配置中可以看到

### http://mp.weixin.qq.com/debug/cgi-bin/sandboxinfo?action=showinfo&t=sandbox/index

## ②模板内容
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

## 和风天气控制台

### https://id.qweather.com/

## 还可以去天行数据申请别的接口

## Feedback
ayron1929@gmail.com
