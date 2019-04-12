## at first
学习用，本项目不能通过破解，越权等免费获取视频资源，唯一能做的就是下载已购买的视频，请勿用于非法用途。

## next
针对的是Edusoho网校系统，[Edusoho](http://www.edusoho.com/category/1/cases)在国内还是比较常见的，
它可以下载该网校系统购买过的视频，需求源自自己之前购买视频后有效期一年，之后再想看需要再次购买，于是打算下次购买后将其保存至本地。

## third
### 使用方法
下载项目并安装依赖，本项目基于python3.7！
```
git clone ...
cd edusoho_downloader
pip install -r requirements.txt
```
另外本项目依赖ffmpeg，请自行下载。

运行前，首先设置`settings.py`文件，之后运行`edusoho.py`即可。

## last but not least
免责？严禁用于盗版，后果自负！

## TODO
当前单线程下载很慢，有时间再改为多线程，欢迎PR。