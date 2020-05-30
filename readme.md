# 설치 방벙

1. git clone https://github.com/iu7726/ReidGo_server.git

2. .env 파일 생성 
    - 적용할 .env파일이 없다면 .env.example파일을 복사하여 .example을 제거

3. php container로 접속
    > docker exec -it {containerId} bash

4. /source 이동 후 composer install

5. key 생성
    > php artisan key:generate

6. exit로 컨테이너 탈출

7. docker-compose up -d

8. localhose:8000

