- helm template . values.yaml
enable hiç tanımlanmazsa renderla
helm template . -f values.yaml | docker compose -f - = docker composede ayağa kaldırıyor
enable -> enabled
2 command olmaz olamaz
docker compose yükle öyle dene