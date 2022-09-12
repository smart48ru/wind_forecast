# wind_forecast

Бот-уведомления о ветре в Липецке

## Запуск
Создать файл `.env`:
```shell
export BOT_TOKEN="1234567890:VCDRJHGYUIKMNBGYUIKMNBvfr45678iuyhgtfr567u"
export DEBUG=1
export SERVE_PORT=8000
export SERVE_HOST=127.0.0.1
```

Выполнить для запуска локально:
```shell
make run.bin
```

Доступные команды:
```shell
build.bin           Build bin file from go
build.img           Build docker image
clean               Clean all artifacts
down.dc             Down Docker compose
fmt                 Run go fmt
help                Show this help message
install-deps        Install all requirements
lint                Run golangci-lint
run.bin             Run as binary
run.cmd             Run as go run cmd/app/main.go
run.dc              Run in Docker
test                Run all test
vet                 Run go vet ./...
```