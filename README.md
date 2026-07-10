# 📜 Índice

- [⚙️ Instalação PNETLAB](#pnetlab)
- [⚙️ Instalação do Ishare2](#ishare2)
- [⚙️ Instalação do Client Pack](#client)
- [⚙️ Referências](#referencias)

## 🛠️ Instalação do PNETLAB<a id="pnetlab"></a>

-  Realize o Download do Linux Ubuntu Server 20.04.6 LTS
```linux
https://releases.ubuntu.com/20.04.6/ubuntu-20.04.6-live-server-amd64.iso
```

-  Instale o Ubuntu Server em um ambiente bare metal ou virtualizado de sua preferência (VMware Workstation, ESXI, Proxmox, Hyper-V, VirtualBox, QEMU, etc)
-  Faça o download do instalador offline do PNETLAB v6 ajustado para o PHP 7.4, no link abaixo:
```linux
https://canalsecinfra.sharepoint.com/:u:/s/Arquivos/IQD-zLKcmrPlRYkfY6XwvvnvATe3ADydvjLVRNbIC7MW-IQ?e=UWCilP
```
- Faça upload desse arquivo para a VM Ubuntu, na pasta /tmp
- Instale a aplicação "unzip"
```linux
sudo apt install unzip
```
- Entre na pasta /tmp e descompacte o arquivo offline-pnetlab-v6-ajustado_php74.zip
```linux
cd /tmp
unzip offline-pnetlab-v6-ajustado_php74.zip
```
- Acesse a pasta offline-pnetlab-v6-ajustado_php74, dê permissão de execução ao arquivo install_pnetlab_v6
```linux
cd offline-pnetlab-v6-ajustado_php74/
chmod +x install_pnetlab_v6.sh
```
- Execute o instalador
```linux
sudo ./install_pnetlab_v6.sh
```
- Reinicie o servidor
```linux
sudo reboot
```
- Faça login com usuário root e senha pnet, e continue o setup, após isso, o servidor será reiniciado novamente, e após reiniciar, você poderá acessar o PNETLab pela URL que mostrará na tela inicial de login do Ubuntu.

## 🛠️ Instalação do Ishare2<a id="ishare2"></a>

-  Comando para instalar o Ishare2 (Download de Imagens):
```linux
wget -O /usr/sbin/ishare2 https://raw.githubusercontent.com/ishare2-org/ishare2-cli/main/ishare2 && chmod +x /usr/sbin/ishare2 && ishare2
```

## 🛠️ Instalação do Client Pack<a id="client"></a>

-  Você pode realizar a instalação do Client Pack e acessar os ativos do laboratório através do putty, vnc, etc (se você já tiver o do EVE-NG, é o mesmo):

- **Link**🔗 https://mega.nz/file/G5liXYzK#oaSC1Jrh5m0HaNkReirurtrXhIHGw6NOZX3jgus1xqo


## 📌 Referências<a id="referencias"></a>
- **LABHUB:** 🔗 https://labhub.eu.org
- **ISHARE2:** 🔗 https://github.com/ishare2-org

