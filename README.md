# food-docker
## 실행하기
아래의 커맨드를 실행하여, 어플리케이션에서 이용하는 미들웨어를 기동할 수 있습니다.

```
docker-compose up -d --build
```

## 설명
어플리케이션에서 이용하는 미들웨어는 다음과 같습니다.

### mongodb
![](https://d1q6f0aelx0por.cloudfront.net/product-logos/56777183-336b-4c18-8bb9-187f71df6ec0-mongo.png)

#### Docker로 기동하기
https://store.docker.com/images/mongo

#### 어플리케이션에서 mongodb접속하기 
- docker-build/mongodb/mongod.conf
  - default port번호 27017(default)
  - bintIp : 외부에서 접속가능한 ip 

#### 참고
- Windows에서 볼륨으로 호스트 디렉토리를 명시적으로 지정하면 기동시 퍼미션 에러가 발생하므로 호스트 디렉토리를 명시적으로 지정하지 않았습니다.
