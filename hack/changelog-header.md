### Linux

```shell
curl -L https://github.com/jenkins-x-plugins/jx-application/releases/download/v{{.Version}}/helmboot-linux-amd64.tar.gz | tar xzv 
sudo mv helmboot /usr/local/bin
```

### macOS

```shell
curl -L  https://github.com/jenkins-x-plugins/jx-application/releases/download/v{{.Version}}/helmboot-darwin-amd64.tar.gz | tar xzv
sudo mv helmboot /usr/local/bin
```

