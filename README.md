
# go-template

A barebones Go app, which can easily be deployed to Dokku.

## Running Locally

Make sure you have [Go](http://golang.org/doc/install) version 1.12 or newer

```sh
$ git clone https://github.com/bywachira/go-template.git
$ cd go-template
$ go build -o bin/go-template -v . # or `go build -o bin/go-template.exe -v .` in git bash
github.com/mattn/go-colorable
gopkg.in/bluesuncorp/validator.v5
golang.org/x/net/context
github.com/heroku/x/hmetrics
github.com/gin-gonic/gin/render
github.com/manucorporat/sse
github.com/heroku/x/hmetrics/onload
github.com/gin-gonic/gin/binding
github.com/gin-gonic/gin
github.com/heroku/go-template
$ heroku local
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Documentation

For more information about using Go on Dokku, see these Dev Center articles:

