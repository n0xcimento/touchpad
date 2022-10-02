# Touchpad.sh
O script foi desenvolvido com intuíto de resolver um problema que sempre tive em distribuições Linux, que era na utilização da tecla de atalho que ativa/desativa o touchpad, do notebook. Logo, em síntese, o script ativa/desativa o touchpad do notebook, em ambientes Linux.

## Dependências
O script utiliza o comando `xinput` para ativar/desavitar o dispositivo. Assim, antes de rodar o `touchpad.sh` é bom se certificar se o comando está disponível em seu ambiente. Caso o `xinput` não esteja disponível, use o seguinte comando para instalá-lo:

`sudo apt install xinput` | Distribuições baseadas em **Debian**

`sudo pacman -Syu xorg-xinput` | Distribuições baseadas em **Arch**

Com as dependências já resolvidas, para executar o `touchpad.sh` é necessário dar permissão de execução para o mesmo. Assim, no diretório onde o arquivo se encontra, execute o seguinte:

`sudo chmod u+x touchpad.sh`

Agora é rodar o script com `./touchpad.sh` :)


## Instruções de uso
Como eu havia dito, o script foi criado para utilizar o teclado de atalho do notebook. Dessa forma, a seguir estarão as instruções para configurar a tecla e utilizar o script.

As instruções seguintes foram realizadas em ambiente xfce. Logo, em ambientes diferentes os passos podem mudar um pouco.

Abra as configurações de seu sistema e siga os passos.

![](https://i.imgur.com/FC2F4Xn.png)

![](https://i.imgur.com/dI3G4nG.png)

![](https://i.imgur.com/IyRvYYy.png)

Clique no ícone destacado, encontre e selecione o arquivo `touchpad.sh`

![](https://i.imgur.com/V2jZ93f.png)

Selecionado o arquivo, clique em OK. Em seguida aparecerá uma janela pedindo para especificar uma tecla. Aqui, clique na tecla de ativação do touchpad do seu teclado.

Feito os passos anteriores, a tecla de atalho de ativação do touchpad do notebook já estará ativando/desativando o touchpad.