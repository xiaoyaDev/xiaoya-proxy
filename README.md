# Xiaoya Proxy

小雅容器代理工具，确保 UA 统一。

## Run

```shell
docker run -d \
    --name=xiaoya-proxy \
    --restart=always \
    --net=host \
    -e TZ=Asia/Shanghai \
    ddsderek/xiaoya-proxy:latest
```

## 许可证

此项目根据 GNU General Public License v3.0 许可证进行许可，详见[`LICENSE`](LICENSE) 文件。
