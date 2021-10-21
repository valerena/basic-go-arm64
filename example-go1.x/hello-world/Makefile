.PHONY: build-HelloWorldFunction

build-HelloWorldFunction:
	CGO_ENABLED=0 GOOS=linux GOARCH=arm64 go build -ldflags "-X main.Version=$(VERSION)" -o ${ARTIFACTS_DIR}/bootstrap
