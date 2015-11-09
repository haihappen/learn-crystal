Compare Ruby and Crystal's performance against each other:

```sh
MAX=1000 ruby server.rb
ab -n 1000 http://localhost:2345/

MAX=1000 ./server
ab -n 1000 http://localhost:2345/
```

Interestingly they both show very similar results. We means either Ruby is
already very well optimized, or Crystal's optimizations aren't a good as thought.
