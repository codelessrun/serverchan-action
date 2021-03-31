# server酱 通知

### 使用

使用server酱发送通知
更多访问官网 http://sc.ftqq.com

参数: 
  + SendKey server酱的 SendKey
  + text 通知的标题,必选
  + desp 通知的内容正文，可选


例如：
```
- name: 通知
  uses: codelessrun/serverchan-action@v1
  with:
    sendKey: ${{ secrets.sendKey }}
    text: your text
    desp: your desp
```