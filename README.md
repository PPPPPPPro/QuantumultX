修改自[@ClydeTime](https://github.com/ClydeTime)大佬的BILIBILI签到脚本:  
1.自动投币为0  
2.银瓜子兑换成功不通知  
  
使用方法:  
1.重写中添加[BilibiliGetCookie.conf](https://raw.githubusercontent.com/PPPPPPPro/QuantumultX/main/BilibiliGetCookie.conf)  
2.HTTP请求中右上角+添加[bilibili.js](https://raw.githubusercontent.com/PPPPPPPro/QuantumultX/main/bilibili.js),cron表达式可以写[0 7 * * *],表示每天早上七点运行  
3.打开哔哩哔哩客户端获取cookie,应该会跳cookie获取成功的通知.cookie获取成功后可以把对应重写关掉.一次获取大概能持续不到一周的时间  
4.打开HTTP请求,左划bilibili.js,点击第三个编辑,右上角播放键运行  
