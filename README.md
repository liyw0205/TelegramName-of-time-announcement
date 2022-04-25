##运行环境
python

##申请Telegram API

选择创建应用：https://my.telegram.org只要填App title和Short name即可，获得api_id和api_hash。

##安卓使用termux运行

下载Termux：https://wwu.lanzoul.com/iB8ZD03r51eb
密码：dsfb

##依次输入以下命令

pkg update
pkg upgrade
pkg install git

##下载库

git clone https://github.com/3418359665/TelegramName-of-time-announcement.git

##安装python

pkg install python

##安装依赖

cd Telegram-Name-Updating
pip install -r requirements.txt
##启动

python tg_username_update.py

依次输入api_id，api_hash，手机号（国区要加+86如+86123********），验证码，如果账号开启了二次验证则根据提示再输入二次验证的密码后启动成功
