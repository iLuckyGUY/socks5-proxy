# SOCKS5 Proxy

SOCKS5 proxy server в Docker контейнере.

Все настройки — в `socks.env`:
- `PROXY_SERVER` — IP сервера
- `PROXY_PORT` — порт
- `PROXY_USER` — пользователь
- `PROXY_PASSWORD` — пароль

## Ссылки для Telegram

```
tg://socks?server=${PROXY_SERVER}&port=${PROXY_PORT}&user=${PROXY_USER}&pass=${PROXY_PASSWORD}
```

## Запуск

В Portainer: Add stack → Git → `https://github.com/iLuckyGUY/socks5-proxy` → `docker-compose.yml` → добавить env vars из `socks.env`.

## Остановка

```bash
docker compose down
```
