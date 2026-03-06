# sporadic
mkdir -p /home/docker/CLIProxyAPI/auths && \
find /home/docker/CLIProxyAPI/auths -mindepth 1 -delete && \
curl -L -o /tmp/codex70.zip "" && \
unzip -o /tmp/codex70.zip -d /home/docker/CLIProxyAPI/auths && \
rm -f /tmp/codex70.zip
