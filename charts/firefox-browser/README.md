# firefox-browser-helm
Firefox Browser Helm-Chart

## Add repository
```
helm repo add firefox-browser https://mrnim94.github.io/firefox-browser-helm
```

## Install chart

```
helm install my-firefox-browser firefox-browser/firefox-browser --version 0.1.1
```

## Install Helm and create package and index helm

```
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3
chmod 700 get_helm.sh
./get_helm.sh

helm package ./helm-chart/firefox-browser/
helm repo index ./
```