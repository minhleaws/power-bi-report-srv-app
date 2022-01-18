## How to

helm install -g --dry-run ./
helm install -g --dry-run --set image.tag=123456 ./

helm upgrade --install power-bi-rp ./
helm uninstall power-bi-rp
