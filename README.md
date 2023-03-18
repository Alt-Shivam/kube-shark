# kube-shark

## Install kubeshark
```bash
curl -Lo kubeshark https://github.com/kubeshark/kubeshark/releases/download/39.1/kubeshark_linux_amd64 && chmod 755 kubeshark
```
```bash
sh <(curl -Ls https://kubeshark.co/install)
```

## Start Monitoring on full cluster
```bash
kubeshark tap -A
```

## Start monitoring on a namespace
```bash
kubeshark tap -n kube-system
```
