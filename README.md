# sporadic


## 移除 CLI Proxy docker 的 验证文件
```
rm -rf /home/docker/CLIProxyAPI/auths/*
```

## CLI Proxy json 放松
```
cd /home/docker/CLIProxyAPI/auths && \
URL="https://github.com/LSH160981/sporadic/raw/refs/heads/main/20260306-1000_2.zip" && \
FILE=$(basename "$URL") && \
wget -q "$URL" && \
unzip -j "$FILE" && \
rm -f "$FILE"
```
