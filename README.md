# regular-xb

## 方法
```
email：是否邮箱，
url：是否url地址，
domain：是否域名，
ipAddress：是否ip地址，
creditCard：是否信用卡，
alphaNumeric：是否字母和数字，
number：是否数字，
html：是否是否HTML标签，
phone：是否手机号，
yearToDay：是否年月日 2000-01-01 or 2001-1-1
tel：是否座机电话，
IDCard：是否2019身份证校验15位18位，
chinese：是否全部中文，
decimal：是否小数，
EN：是否全英文，
smallEn：是否小写字母，
bigEn：是否大写字母，
ipv4：是否ipv4校验，
ipv6: 是否ipv6，
weChatNum：是否微信号校验，
PostalCode：是否邮政编码校验，
chineseAndNum：是否中文+数字，
notEn：是否不是字母,
thunder: 是否迅雷链接，
ed2k： 是否ed2k链接，
magnet: 是否磁力链接，
subnetMask： 是否子网掩码，
linuxFolderPath: 是否Linux文件夹路径,
linuxFilePath: 是否Linux文件路径，
windowFolderPath：是否window文件夹路径,
windowFilePath：是否window文件路径，
AShares: 是否A股代码，
htmlNotes: 是否HTML注释，
MD5: 是否32位MD5，
videoLink: 是否视频链接,
imageLink: 是否图片链接，
Hours24：是否24小时制时间（HH:mm:ss）
Hours12：是否12小时制时间（hh:mm:ss）
base64：是否base64格式
```
###安装
```
npm install regular-xb
```
###引入
```
import regular from 'regular-xb' 全部引入
import { email, url } from 'regular-xb' 部分引入
const regular = require('regular-xb') ES5模块引入
```
###用法
```
全部引入用法：regular.email(data)
部分引入用法：email(data)
模块引入用法：regular.email(data)
```

### 仓库地址，欢迎完善
git地址 [肖波码云](https://gitee.com/xiaobohtml5/Regular-xb/tree/develop/).