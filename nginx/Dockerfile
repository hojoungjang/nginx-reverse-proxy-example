FROM nginx:latest

# 앞서 만든 인증서와 개인키를 잘 복사해 주자
COPY cert.crt /etc/ssl/certs/cert.crt
COPY cert.key /etc/ssl/private/cert.key

# 앞서 만든 nginx 설정 파일도 잘 복사해 주자
COPY nginx.conf /etc/nginx/nginx.conf