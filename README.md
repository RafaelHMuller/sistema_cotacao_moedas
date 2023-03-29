<h1 align="center">
📄<br>README - Projeto Sistema Cotação Moedas
</h1>

## Índice 

* [Descrição do Projeto](#descrição-do-projeto)
* [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)
* [Pré requisitos](#pré-requisitos)
* [Execução](#execução)
* [Bibliotecas](#bibliotecas)

# Descrição do projeto
> Este repositório é meu projeto Python de criação de sistema para coleta de cotações atualizadas de moedas. O objetivo do projeto foi a criação de um sistema, por meio de janela Tkinter, no qual o usuário pode receber informações atualizadas da cotação de uma ou mais moedas. As cotações são retiradas diretamente de uma api.

# Funcionalidades e Demonstração da Aplicação
Cadastro de sistema (janela Tkinter) de cotação atualizada de moedas.

Sistema Tkinter:<br>
![Screenshot_1](https://user-images.githubusercontent.com/128300382/228549084-3895f968-11ba-4c28-b0c4-c8ae346206d5.png)

Atualização de planilha Excel com as cotações das moedas de interesse:<br>
![Screenshot_2](https://user-images.githubusercontent.com/128300382/228549402-c66e2147-7314-45ba-88e1-fd99deb47b3c.png)

## Pré requisitos

* Sistema operacional Windows
* IDE de python (ambiente de desenvolvimento integrado de python)
* Bases de dados (arquivo Excel)

## Execução

Ao ser executado, o código abre uma janela interativa ao usuário. Por meio deste sistema, é possível coletar a cotação atualizada de uma moeda em uma data específica, bem como de várias moedas em uma base de dados Excel, desde que neste arquivo xlsx as moedas estejam em uma única coluna e com suas respectivas siglas digitadas corretamente (ex.: Dólar = USD, Euro = EUR, Bitcoin = BTC). Ao clicar em finalizar, o arquivo xlsx será atualizado com as cotações do período escolhido.

## Bibliotecas

* <strong>tkinter, tkcalendar, tkinter.filedialog:</strong> bibliotecas de criação e edição de janela Tkinter<br>
* <strong>pandas:</strong> bibliotecas de integração de arquivos excel, csv e outros, possibilitando análise de dados<br>
* <strong>requests, json:</strong> bibliotecas que permitem a integração de APIs - Interface de Programação de Aplicações<br>
* <strong>datetime:</strong> biblioteca que permite a utilização de data e hora<br>
