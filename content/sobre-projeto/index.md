---
title: 'Sobre o Projeto'
---

O meu projeto de PAP (Projeto de Aptidão Profissional) consiste na criação de um assistente pessoal (semelhante a Google Assistant &reg; e Amazon Alexa &reg;), mas mais simples e fácil de utilizar.

O projeto é ***Open Source*** e o código fonte encontra-se disponível para consulta por todos em [https://github.com/pyVoice/pyVoice](https://github.com/pyVoice/pyVoice).

## Inspiração

Este projeto surgiu devido ao meu interesse pela área de _Machine Learning_ e manipulação de voz/áudio.

A linguagem de programação Python foi escolhida para esta tarefa devido à sua simplicidade e bibliotecas disponíveis.

## Visão Geral

O projeto engloba três áreas, que ao funcionarem em conjunto permitem o funcionamento da aplicação.

Abaixo está o funcionamento geral da aplicação.

### Reconhecimento de voz

<img src="images/speech_to_text.svg" class="image-about center" />

Responsável por converter a voz do utilizador (obtida através do microfone do dispositivo) para texto, que o computador consegue processar.

### *Matching* de *input* com comandos

<img src="images/matching.svg" class="image-about center" />

Após o *input* de áudio ter sido convertida para texto, será comparada com padrões de comandos pré-definidos, decidindo assim a melhor resposta.

### Conversão de texto para voz

<img src="images/text_to_speech.svg" class="image-about center" />

A resposta ao pedido do utilizador será convertida para voz e reproduzida no dispositivo, permitindo assim que o utilizador nem perca tempo a ler a resposta!


