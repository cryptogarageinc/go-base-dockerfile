# go-base-dockerfile

## build

docker buildx build [--platform \<target platform\>] [-t \<tag\>] -f sharedlib.dockerfile .

## format and lint

```sh
go run github.com/go-task/task/v3/cmd/task@latest format lint
```
