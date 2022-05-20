# AWS S3 과정

## 1. 버킷만들기 클릭
![01](/AWS/img/01.JPG)

## 2. 버킷 이름 = 내가 할 도메인 주소 입력
![02](/AWS/img/02.JPG)
ex) stopu.com / .io / .pro / .net ...    

## 3. 이름(stopu.io) 클릭
![03](/AWS/img/03.JPG)

## 4. 속성 -> 스크롤 마지막 정적 웹 사이트 호스팅
![09](/AWS/img/09.JPG)
![11](/AWS/img/11.PNG)

## 5. 인덱스 문서 항목에 내가 올릴 html파일의 이름과 동일하게 작성
![12](/AWS/img/12.PNG)
## 6. 권한 -> 퍼블릭 엑세스 차단(버킷 설정) 클릭
![04](/AWS/img/04.JPG)

## 7. 체크박스 전체 해제
![05](/AWS/img/05.JPG)
![06](/AWS/img/06.JPG)

## 8. 버킷 정책에서 편집 클릭
![07](/AWS/img/07.JPG) 


## 9. 밑에 버킷정책 복사 후 도메인주소에 2번에서 만든 도메인 입력
![08](/AWS/img/08.JPG)
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
## 10. 속성 클릭
![09](/AWS/img/09.JPG)

## 11. 스크롤 끝에 주소 생성 됨
![10](/AWS/img/10.JPG)