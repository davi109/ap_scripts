# ap_scripts
Repositório contento scripts para instalação do controlador wireless em um ponto de acesso com OpenWrt

Para instalação, acesso o terminal de seu roteador wireless com OpenWrt e execute os seguintes comando:

```console
opkg update
opkg install curl
curl -LJO https://raw.githubusercontent.com/davi109/ap_scripts/main/install/install.sh; chmod +x install.sh
```

Logo após, execute o arquivo baixado com o comando:

```console
./install.sh -h 'controller_server' -u 'api_user' -p 'api_password'```

