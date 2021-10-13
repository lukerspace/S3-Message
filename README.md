# AWS S3

### S3 , CDN , ACM , ROUTE53

透過 AWS (CloundFront) CDN 服務，將檔案傳送 S3 BUCKET 部屬， 將 CDN 備用網域 (CNAME) 匯入 ACM 憑證託管，並使用 ROUTE53 去使臨時域名作更新。

1. Upload image and text to the S3 meanwhile create a URL.
2. Insert url & text into MySql database.
3. Api fetch the database
4. javascript visualize the data
