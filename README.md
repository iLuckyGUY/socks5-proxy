# SOCKS5 Proxy

SOCKS5 proxy server в Docker контейнере.

- **Сервер:** `212.43.151.109`
- **Порт:** `1080`
- **Пользователь:** `webup`
- **Пароль:** в `socks.env` (`PROXY_PASSWORD`)

## Ссылки для Telegram

```
tg://socks?server=212.43.151.109&port=1080&user=webup&pass=<PASSWORD>
```

> `<PASSWORD>` — значение `PROXY_PASSWORD` из `socks.env`.

## Запуск

В Portainer: Add stack → Git → `https://github.com/iLuckyGUY/socks5-proxy` → `docker-compose.yml`

## Остановка

```bash
docker compose down
```
