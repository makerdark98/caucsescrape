# CAUCSE_SCRAPPING

`node version >= 8.4.0`


```
npm install cheerio node-schedule promise sqlite3 winston selenium-webdriver
```


chromedriver (firefox 사용 불가!)

* x86_64
```
wget https://chromedriver.storage.googleapis.com/2.31/chromedriver_linux64.zip
```

* armv7l
```
wget https://github.com/electron/electron/releases/download/v1.6.0/chromedriver-v2.21-linux-armv7l.zip
```


* 실행
```
mkdir db
mkdir log
node scrapping.sh
```
