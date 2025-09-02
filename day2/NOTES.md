# Day 2 — Linux и Nginx в Docker
- Контейнер Ubuntu с монтированием /work: базовые команды (ls/cd/pwd, touch/cp/mv/rm), chmod u+x, ./hello.sh.
- Переменные окружения (PATH), процессы (ps/top), сеть (curl/ping).
- Nginx: docker run -d -p 8080:80 -v "$PWD/day2/site:/usr/share/nginx/html:ro" nginx:alpine.
- Страница открывается на http://localhost:8080.
