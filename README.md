# gongrok
golang ngrok wrapper


## Install

 -  [ngrok](https://ngrok.com/download)
```
go get github.com/revzim/gongrok
```

## Example
- [WEB APP EXAMPLE](https://github.com/revzim/gongrok/example/webapp)
  - place ngrok binary download in ngrok path ```./ngrok_bin/```
  - build or run
    - ```go run main.go | go build main.go```
    - server will start & client located at ```http://localhost:8080/client```
