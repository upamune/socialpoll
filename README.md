## Setting Envvar
```sh
export SP_TWITTER_KEY=
export SP_TWITTER_SECRET=
export SP_TWITTER_ACCESSTOKEN=
export SP_TWITTER_ACCESSSECRET=
```

### Start Daemons

```
$ nsqlookupd
$ nsqd --lookupd-tcp-address=127.0.0.1:4160
$ mongod --dbpath ./db
```

