# Golang-DALEE2-linebot-Render
# 一個Golang DALEE2 linebot專案，快速建置於平台Render。


### [English](https://github.com/pyfbsdk59/Golang-DALEE2-linebot-Render/blob/main/README.md)
### [日本語](https://github.com/pyfbsdk59/Golang-DALEE2-linebot-Render/blob/main/README_jp.md)


#### 1. 本專案參考了以下前輩和官方的方案改成製作：
https://github.com/kkdai/chatgpt<br>
https://github.com/line/line-bot-sdk-go<br>
https://github.com/kkdai/LineBotTemplate

#### 2. 請先fork本專案到自己的Github帳號裡。然後前往Render網站中設定，選擇新增「Web Services」，可用Github帳號匯入此專案，然後設定自己的名稱和選擇免費free方案。記得按下方「Advanced」，設定環境變數。


#### 3. 必須在Render的Environment Variables設定3個環境變數，分別是OPENAI_TOKEN，也就是OPENAI的api key，接著尚有line的環境變數CHANNEL_SECRET和CHANNEL_TOKEN。設定好後開始部屬，可能要花上一些時間。成功後複製自己的URL到Line developer網頁設定Webhook URL。例如：

https://xxx.onrender.com/callback

------
#### Line和openai api設置請參考： 

https://github.com/howarder3/GPT-Linebot-python-flask-on-vercel
