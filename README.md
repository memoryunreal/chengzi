# chengzi
## Chinese-OCR-PDF
1. 环境安装
- [Poppler](https://github.com/Belval/pdf2image#windows) 依赖安装 (windows)
    - Mac
    ```code
    brew install poppler
    ``` 
    - Linux
    ```code
    conda install -c conda-forge poppler
    pip install pdf2image
    ```
- python 包安装
```code
cd ./chinese-pdf-ocr
pip install -r requirements.txt
```

2. 使用流程
- 先启动flask server，然后用ngrok隧道穿透
```code
# 启动flask server
cd ./chinese-pdf-ocr/demo_web 
python main.py

# 隧道使用 会输出5000端口对应的外网可以访问的网址
./ngrok http 5000(port)
```
