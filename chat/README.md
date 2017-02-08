# Chat Application in Go with Websockets

**Build:**
```
go get github.com/fimassuda/goblueprints
go get github.com/clbanning/x2j
# bzr should be installed
go get labix.org/v2/mgo/bson
go build -o ../dist/chat
```

**prereqs:**
```
export GOOGLE_CLIENT_ID=<YOUR_CLIENT_ID>
export GOOGLE_SECRET_KEY=<YOUR_SECRET_KEY>
```

**run:**
```
../dist/chat --addr=":8080"
```

Open two tabs in the browser to enjoy the conversation