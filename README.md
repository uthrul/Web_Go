# web go
Writing a Web Application in Go.
=======================================

0. package
```
package main

func main() {
	
}
```

1. install gorilla mux.
- go get -u github.com/gorilla/mux

2. for Redis database
- go get -u github.com/go-redis/redis
- brew install redis
- run server : redis-server & redis-cli
- stop server : redis-cli shutdown

3. gorilla sessions
-  go get -u github.com/gorilla/sessions

4. crypto
- go get golang.org/x/crypto/bcrypt