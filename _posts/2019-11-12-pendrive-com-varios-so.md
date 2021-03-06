---
layout: post
title: "Pendrive bootável com vários Sistemas Operacionais"
categories: ['Manutenção']
authors: ['Raphael Alves Dias'] 
tags: ['Pendrive bootável']
description: 'Aprenda a criar o seu próprio pendrive com vários sistemas embarcados'
image: flash-memory-1306886_960_720.jpg
---

### Entendendo um pendrive bootável
Boa parte dos notebooks atuais não trazem os leitores de CD/DVD. Isso favoreceu o desenvolvimento de aplicativos que permitam criar pendrives de boot para a instalação de algum Sistema Operacional.


### Yumi Multiboot

O Yumi é um software gratuito que permite criar um pendrive de boot com vários sistemas operacionais. Ele também oferece ferramentas de inicialização pré-estabelecidas, ou seja, ele informa onde baixar o arquivo ISO, caso o usuário não o tenha.

Download: [Yumi Multiboot.](https://www.pendrivelinux.com/yumi-multiboot-usb-creator/)

Após fazer o download do aplicativo, realize o download do arquivo ISO dos sistemas opeacionais desejados.


### Criando um pendrive bootável

Primeiro execute o aplicativo baixado. Após isso aparecerá uma tela igual a de baixo, e então clique em **I Agree** para concordar com os termos de uso e prosseguir.
![Error](/42/images/post/yumi1.jpg " ")

O software será executado direto, sem ser necessário instalar no computador. E então aparecerá a tela abaixo.

![Error](/42/images/post/yumi2.jpg " ")

Escolha o pendrive que será usado para a criação e transferências dos Sistemas Operacionais.

![Error](/42/images/post/yumi3.jpg " ")

Caso seja a primeira transferência de um Sistema Operacional para o pendrive, clique em **Format** para formatar e preparar o pendrive. Veja a seguir nas imagens:

![Error](/42/images/post/yumi4.jpg " ")
![Error](/42/images/post/yumi5.jpg " ")

No **Step 2**, selecionaremos o primeiro Sistema Operacional que será transferido para o pendrive (nesse caso selecionei o Linux). Caso não tenha a ISO baixada, clique em **Download Link**. 

![Error](/42/images/post/yumi6.jpg " ")

Depois de selecionar o Sistema Operacional para colocar no pendrive, clique em **Browse** para localizar e selecionar a ISO do Sistema. Logo após clique em **Abrir**.

![Error](/42/images/post/yumi7.jpg " ")

Agora clique em **Create** para copiar o Sistema Operacional para o pendrive.

![Error](/42/images/post/yumi8.jpg " ")

Logo após aparecerá a tela abaixo que irá preparar o pendrive para ser inicializável (bootável).

![Error](/42/images/post/yumi9.jpg " ")

Clique em **Sim** para começar a copiar o Sistema Operacional.

![Error](/42/images/post/yumi10.jpg " ")
![Error](/42/images/post/yumi11.jpg " ")

Após finalizar, aparecerá a tela abaixo perguntando se você deseja copiar outro Sistema Operacional. Clique em **Sim** para escolher outro Sistema Operacional.

![Error](/42/images/post/yumi12.jpg " ")

A tela inicial do **YUMI** aparecerá novamente. Realize os mesmos procedimentos, **exceto** clicar em Format , pois, se essa opção for marcada, o Sisma Operacional copiado anteriormente será apagado. 

![Error](/42/images/post/yumi13.jpg " ")
![Error](/42/images/post/yumi14.jpg " ")

Agora selecione o outro Sistema Operacional desejado, e selecione a ISO. E então clique em **Create** para iniciar o processo de cópia novamente.

![Error](/42/images/post/yumi15.jpg " ")
![Error](/42/images/post/yumi16.jpg " ")

A cópia estará sendo realizada.

![Error](/42/images/post/yumi17.jpg " ")

Ao terminar a cópia do Sistema Operacional, aparecerá a tela perguntando se você deseja fazer outra cópia. Caso você queira, clique em **Sim**, caso não queira, clique em **Não** e o programa será encerrado e o pendrive estará pronto para o uso.

Depois, basta selecionar o pendrive bootável como a primeira opção de boot, e então instalar o tão desejado Sistema Operacional.

Agradeço !













