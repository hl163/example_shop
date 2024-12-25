# 学习 kitex
https://www.cloudwego.io/zh/docs/kitex/getting-started/

# Make kitex_gen
```
kitex -module example_shop -service example.shop.item -use example_shop/kitex_gen ../../idl/item.thrift

```

# Service

## build Service

```
cd rpc/item
bash build.sh
```

## Run Service

```
cd rpc/item/output
bash bootstrap.sh
```

# Client

## Run Client

```
cd api/
go run .
```