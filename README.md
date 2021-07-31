# AWS S3

S3 bucket , CDN , ACM , ROUTE53

在 S3 BUCKET 上傳靜態檔案並且透過 CDN 去將 S3 部屬，透過 CDN 將備用網域 CNAME 託管，並在 ACM 請求匯入託管的憑證(安全性，名字一致)
透過 ROUTE53 去使臨時域名作更新

完成使用 CDN 去訪問將被託管的 S3 BUCKET

<img src=readme.png/>
