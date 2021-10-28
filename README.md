# PROJETO-BREAKOUT
Projeto de confecção de um jogo baseado no jogo Breakout, atualmente ainda em desenvolvimento por Aríthissa Vitória e Lucas Silva Neves.

UNIVERSIDADE DE SÃO PAULO
INSTITUTO DE CIÊNCIAS MATEMÁTICAS E DE COMPUTAÇÃO


## 1. SOBRE O JOGO

O jogo a ser desenvolvido será baseado no jogo eletrônico Breakout, inicialmente desenvolvido para arcade pela Atari e lançado no ano de 1976. Posteriormente, o jogo original foi atualizado para console com o nome de Super Breakout.


## 2. OBJETIVO

O jogo original consiste em uma ou mais plataformas controladas pelo jogador conforme o mesmo passa pelas fases, cujo objetivo é rebater uma ou mais bolinhas, impedindo que caiam fora da plataforma, para destruir todos os blocos alinhados no topo da tela.


## 3. ESPECIFICAÇÕES

A versão do jogo a ser desenvolvida para a disciplina seguirá os princípios base do jogo original, porém com uma fase contendo duas ou mais bolinhas e duas plataformas, a serem controladas simultaneamente pelo jogador através do uso de threads. Além disso, nesta versão, alguns blocos destacados serão regiões críticas nas quais duas ou mais bolinhas não poderão acessar juntas, ou seja, blocos que só poderão ser destruídos por apenas uma bolinha, utilizando o conceito de semáforos. Blocos especiais poderão ocasionar uma explosão que param a movimentação das bolinhas que estiverem em uma determinada área; caso todas as bolinhas parem, é declarado fim de jogo.


