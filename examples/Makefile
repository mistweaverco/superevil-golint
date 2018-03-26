all: lint build

lint:
	go lint ./src/...

build: build-linux build-windows build-mac

build-linux:
	exportGOOS="linux";\
	go build -ldflags="-s -w" -o dist/evil-example src/main.go;

build-windows:
	export GOOS="windows";\
	go build -ldflags="-s -w" -o dist/evil-example.exe src/main.go;

build-mac:
	export GOOS="darwin";\
	go build -ldflags="-s -w" -o dist/evil-example.app src/main.go;

optimize-linux:
	upx --brute dist/evil-example

optimize-windows:
	upx --brute dist/evil-example.exe

optimize-mac:
	upx --brute dist/evil-example.app

optimize: optimize-linux optimize-windows optimize-mac

