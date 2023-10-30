### SSH鍵ファイルをダウンロード

### SSH鍵ファイルのパーミッションを変
```
chmod 600 pem_ibmcloudvsi_download.pem
```

### SSH鍵でUbuntuサーバーにログイン
```
ssh itzuser@162.133.113.47 -p 2223 -i pem_ibmcloudvsi_download.pem
```
