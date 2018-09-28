# 主页
**********************
https://lwc.im  
https://m.lwc.im

*********************
## 1. 音乐
`<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=270 src="//music.163.com/outchain/player?type=0&id=2437407323&auto=1&height=430"></iframe>`  
  

### 1.1 更改歌单
将id=后面的数字改成想要的歌单id
 

### 1.2 播放器大小 
修改width= height= ,大小自己调试  
  
**********************
## 2. 自动跳转手机页面
`    <script type="text/javascript">
            try {
                var urlhash = window.location.hash;
                if (!urlhash.match("fromapp")) {
                    if ((navigator.userAgent.match(/(iPhone|iPod|Android|ios|iPad)/i))) {
                        window.location = "https://欲跳转的手机域名";
                    }
                }
            } 
            catch (err) {
            }
    </script>`  
    将想要跳转的手机域名填入window.location后面  
    整段代码放入`<head></head>`中间  

**********************
