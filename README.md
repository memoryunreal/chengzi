# chengzi
## Chinese-OCR-PDF
先启动flask server，然后用ngrok隧道穿透
```code
# 启动flask server
cd ./chinese-pdf-ocr/demo_web 
python main.py

# 隧道使用 会输出5000端口对应的外网可以访问的网址
./ngrok http 5000(port)
```
