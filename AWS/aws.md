버킷이름 -> 도메인주소  
ex) naver.com  
처럼 하는 거  
.com  
.io  
.pro  
.net ... 다양  
가운데 naver부분은 겹치면 안됨  

- 버킷정책
```
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:*",
            "Resource": "arn:aws:s3:::도메인주소/*"
        }
    ]
}
```