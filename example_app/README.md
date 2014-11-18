Example App
================

A [Roda](http://github.com/jeremyevans/roda) API mounted on Rack to demonstrate [newrelic-roda](https://github.com/mikz/newrelic-roda).

* [ping](api/ping.rb): a hello world example that returns a JSON document

Run
___

```
$bundle install
$rackup
```

### Ping

Navigate to http://localhost:9292/api/ping with a browser or use `curl`.

```
$ curl http://localhost:9292/api/ping

{"ping":"pong"}
```

New Relic
---------

The application is setup with NewRelic w/ Developer Mode. Navigate to http://localhost:9292/newrelic after making some API calls.
