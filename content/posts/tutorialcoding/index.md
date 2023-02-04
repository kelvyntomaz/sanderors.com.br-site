---
title: 'Tutorial de coding: seta piscar 3x, desvincular limpador traseiro da marcha ré e mais intervalos do limpador de parabrisa.'
subtitle: 'Um tutorial que permite seta piscar 3x, desvincular limpador traseiro da marcha ré, mais intervalos do limpador de parabrisa e muito mais.'
date: '2021-05-30T15:17:24'
author: 'eduardoprox'
categories: [ Tutorial ]
image: 'coding.png'
---

O Jean Bublitz montou um tutorial para você mexer no coding e mudar/habilitar. Só estamos compartilhando o conteúdo, mas o crédito é todo dele. (Ele traduziu uma porrada de fórum turco pra chegar nisso.)  
  
O que o tutorial permite:


* Desvincular o limpador traseiro quando engatar a marcha ré
* Seta de cortesia (seta pista 3x quando levemente acionada) (serve apenas nos modelos até 2017).
* Mais intervalos do limpador dianteiro (necessário a troca da chave pela da Captur PN à confirmar e solda interna)
* Aviso sonoro de utilização do cinto de segurança (serve apenas nos modelos após 2017)
* Aparecer o relógio no cluster do painel.  
Temperatura externa no cluster do painel.
* Média do carro (km/L ou L/km)
* Aviso sobre mudança de marcha (precisa testar, se é o indicador no painel ou o aviso sonoro dos RS)
* Painel aceso mesmo com os faróis apagados (serve apenas nos modelos até 2017).


![⚠](https://s.w.org/images/core/emoji/14.0.0/72x72/26a0.png) Lembrando: isso é um tutorial da comunidade, feito apenas para ajudar. Não nos responsabilizamos pelo que você fizer. Faça por sua conta e risco.


![⚠](https://s.w.org/images/core/emoji/14.0.0/72x72/26a0.png) Para o tutorial, você precisa de um conector OBD2 que possa usar por notebook – seja bluetooth ou USB. Não funciona em smartphone, mac os, etc.


**Programa**
------------


Certificar-se que o conector OBDII está conectado no carro e pareado/ligado com o computador.


[![⬇](https://s.w.org/images/core/emoji/14.0.0/72x72/2b07.png)](https://drive.google.com/file/d/1utfzgcIWyLH77LW5LKCMgWCP23QUeZ8P/view?usp=sharing) [Baixar aqui e abrir o programa “ddt4all Dacia”](https://sanderors.com/wp-content/uploads/2021/05/ddt4all.zip)


Selecionar “COM4” ou “COM6”


Clicar no símbolo do Bluetooth.


Ativar a caixa “Estou consciente…”


Apertar no botão “Modo Conectado”.


O programa irá inicializar com todas as ECUs disponíveis e conectar com o carro.


A ignição do carro pode ficar na posição I ou II. 


**Modificações**
----------------


**Tipo 1:**


* Desvincular o limpador traseiro quando engatar a marcha ré
* Seta de cortesia (seta pista 3x quando levemente acionada) (serve apenas nos modelos até 2017).
* Mais intervalos do limpador dianteiro (necessário a troca da chave pela da Captur PN à confirmar e solda interna)


Selecionar a ECU > UCH


Clicar duas vezes em “GB BCM T4”.


Selecionar “GB BCM T4” no quadrado abaixo.


E na tela “Ecrãs”, abrir a aba “English BCM”, depois clicar em “Change configurations”.


Na página à direita, irá selecionar “With” ou “Without” para cada modificação que se deseja realizar.


Para salvar, deve-se clicar no ícone do Expert Mode (mini Einstein) no canto superior esquerdo do programa e depois clicar em “Save/Write”. Desabilitar o Expert Mode e pronto!


**Tipo 2:**


* Aviso sonoro de utilização do cinto de segurança (serve apenas nos modelos após 2017).
* Aparecer o relógio no cluster do painel.
* Temperatura externa no cluster do painel.
* Média do carro (km/L ou L/km)
* Aviso sobre mudança de marcha (precisa testar, se é o indicador no painel ou o aviso sonoro dos RS)
* Painel aceso mesmo com os faróis apagados (serve apenas nos modelos até 2017).


Selecionar a ECU > TDB


Clicar duas vezes em “GB CLUSTER”.


Selecionar “GB BCM T4” no quadrado abaixo.


E na tela “Ecrãs”, abrir a aba “Instrument cluster”, depois clicar em “Change configurations”


Na página à direita, irá selecionar “With”, “Without” ou outras configurações específicas para cada modificação que se deseja realizar.


Para salvar, deve-se clicar no ícone do Expert Mode (mini Einstein) no canto superior esquerdo do programa e depois clicar em “Save/Write”. Desabilitar o Expert Mode e pronto.


O post [Tutorial de coding: seta piscar 3x, desvincular limpador traseiro da marcha ré e mais intervalos do limpador de parabrisa.](https://sanderors.com/tutorialcoding/) apareceu primeiro em [Sandero RS](https://sanderors.com).

