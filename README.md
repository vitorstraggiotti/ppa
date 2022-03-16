# How to use
```bash
curl -s --compressed "https://vitorstraggiotti.github.io/ppa/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/vitorstraggiotti.list "https://vitorstraggiotti.github.io/ppa/vitorstraggiotti.list"
sudo apt update
```
