# Rivalz CLI
برای راه اندازی کلاینت پروژه rivalz مراحل زیر را طی کنید


## System Requirements


ابتدا با کامند زیر سرور خود را آپدیت کنید

```bash
apt update && apt upgrade -y
```



```bash
apt install curl
```

```bash
apt install screen
```
```bash
nodejs -v
```
برای نصب نیاز به nodejs ورژن 20 داریم که اگر نصب بود نیاز به نصب مجدد ندارد

برای نصب از کامند های زیر استفاده نمایید
```bash
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
```



```bash
apt install -y nodejs
```


```bash
nodejs -v
```

## Install rivalz



```bash
npm i -g rivalz-node-cli
```


```bash
screen -S rivalz
```
بعد از این کامند وارد یک صفحه جدید می شوید
```
rivalz update-version
```
```bash
rivalz run
```

بعد از وارد کردن کامند های بالا یک سری اطلاعات از شما می خواهد

1.آدرس ولت EVM

2.مقدار CPU که درگیر می شود
 
3.مقدارRAM که اختصاص می دهید

4.نوع هارد را انتخاب کنیدپ

5.سریال هارد را انتخاب کنید( می توانید فقط Enter بزنید)

6.مقدار هاردی که درگیر می شود


>Ctrl+A+D
>



