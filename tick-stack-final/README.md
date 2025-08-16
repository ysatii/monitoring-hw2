# TICK Stack with Configs

Полный проект с конфигами для InfluxDB, Kapacitor и Telegraf.

## Запуск
```bash
docker compose up -d
# Chronograf: http://localhost:8888
```
## Подключение Chronograf
В окне подключения укажи URL: `http://influxdb:8086`, БД: `telegraf`, v2 Auth — выключен.
