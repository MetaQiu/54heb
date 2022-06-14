# 54heb
河北省青年大学习api


* 检查账号有效性

        https://api.54heb.com/checktoken

* 获取个人资料

        https://api.54heb.com/user/index2

* 获取期数id

        https://api.54heb.com/study/studylink

* 开始学习

        https://api.54heb.com/study/statistics?type=new&id=期数id

* 学习记录

        https://api.54heb.com/study/getStudyRecord?page=1

GET请求头  

        Host: api.54heb.com  
        Connection: keep-alive  
        Accept: application/json, text/plain, */*  
        Origin: https://h5.54heb.com  
        User-Agent: Mozilla/5.0 (Linux; Android 10; SEA-AL10 Build/HUAWEISEA-AL10; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/86.0.4240.99 XWEB/3235 MMWEBSDK/20220105 Mobile Safari/537.36 MMWEBID/9846 MicroMessenger/8.0.19.2080(0x2800133D) Process/toolsmp WeChat/arm64 Weixin NetType/WIFI Language/zh_CN ABI/arm64  
        token:   
        VERSION: H5_3.2.0  
        Sec-Fetch-Site: same-site  
        Sec-Fetch-Mode: cors  
        Sec-Fetch-Dest: empty  
        Referer: https://h5.54heb.com/  
        Accept-Language: zh-CN,zh;q=0.9,en-US;q=0.8,en;q=0.7  
        Cache-Control: no-cache  
        Accept-Encoding: gzip, deflate  
        Content-Length: 0  
