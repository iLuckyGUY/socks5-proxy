# SOCKS5 Proxy

SOCKS5 proxy server в Docker контейнере.

Все настройки — в `socks.env`:
- `PROXY_SERVER` — IP сервера
- `PROXY_PORT` — порт
- `PROXY_USER` — пользователь
- `PROXY_PASSWORD` — пароль

## Ссылки для Telegram

**По домену:**
```
tg://socks?server=socks-proxy.cloudweb.name&port=1080&user=webup&pass=<PASSWORD>
```

**Если домен не работает (по IP):**
```
tg://socks?server=212.43.151.109&port=1080&user=webup&pass=<PASSWORD>
```

> `<PASSWORD>` — значение `PROXY_PASSWORD` из `socks.env`.

## Запуск

В Portainer: Add stack → Git → `https://github.com/iLuckyGUY/socks5-proxy` → `docker-compose.yml` → добавить env vars из `socks.env`.

## Остановка

```bash
docker compose down
```
