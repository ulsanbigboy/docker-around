FROM httpd

COPY index.html /usr/local/apache2/htdocs/

# 이미지 생성 명령어 (현 파일과 같은 디렉토리에서)
# docker build -t {이미지명} .

# 컨테이너 생성 & 실행 명령어
# docker run --name {컨테이너명} -p 80:80 -d {이미지명}

# docker build -t httpd-img .
# docker run --name httpd-con -p 80:80 -d httpd-img

# docker inspect httpd-con
# docker exec -it httpd-con bash
