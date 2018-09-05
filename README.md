# bcnode-hybrid with optimized primitives.es6
ref: https://github.com/lgray/bcnode-unpacked/compare/0.7.7...optimizations_077
tg community ref: https://t.me/blockcollideradvanced/39436

Build the new image using something like this:

```
docker build -t "blockcollider/bcnode:0.7.7-ml" .
```

Afterwards, run it as usual:

```
docker run --name bcnode -p 3000:3000 blockcollider/bcnode:0.7.7-ml start --ws --rovers --ui --node --miner-key <YOUR-KEY>
```
