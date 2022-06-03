<img src = "https://github.com/liyw0205/Meitu/blob/main/%E5%A4%87%E4%BB%BD/illust_97361086_20220427_131405.jpg" >



# 运行环境
python

# 申请Telegram API（重要）
[点这里申请API](https://core.telegram.org/api)
选择创建应用程序只要填App title和Short name即可，获得api_id和api_hash。


# Android教程
<details>
<summary>(点击查看)</summary>

[点这下载Termux](https://wwu.lanzoul.com/iB8ZD03r51eb)
密码：dsfb


## 依次输入以下命令
```
pkg update
```
```
pkg upgrade
```
```
pkg install git
```
## 下载库
```
git clone https://github.com/liyw0205/TelegramName-of-time-announcement.git
```

## 安装python
```
pkg install python
```

## 安装依赖
```
cd TelegramName-of-time-announcement
```
```
pip install -r requirements.txt
```

## 启动
```
python tg_username_update.py
```

依次输入api_id，api_hash，手机号（国区要加+86如+86123********），验证码，如果账号开启了二次验证则根据提示再输入二次验证的密码后启动成功
 </details>

# Linux教程
<details>
<summary>(点击查看)</summary>

## 依次输入以下命令
```
apt-get update
```
```
apt-get upgrade
```
```
apt-get install git
```

## 下载库
```
git clone https://github.com/liyw0205/TelegramName-of-time-announcement.git
```

## 安装python
```
apt-get install python3-pip
```
## 安装依赖
```
cd TelegramName-of-time-announcement
```
```
pip3 install -r requirements.txt
```

## 启动
```
python3 tg_username_update.py
```

依次输入api_id，api_hash，手机号（国区要加+86如+86123********），验证码，如果账号开启了二次验证则根据提示再输入二次验证的密码后启动成功
 </details>
